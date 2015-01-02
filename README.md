conky-clock
===========
# Conky Metro Clock - http://fav.me/d424h9d

# Conky settings
background no
update_interval 1

override_utf8_locale yes

double_buffer yes
no_buffers yes

text_buffer_size 2048

# Window specifications
own_window yes
own_window_class conky
own_window_transparent yes
own_window_hints undecorate,below,sticky,skip_taskbar,skip_pager

border_inner_margin 0
border_outer_margin 0

alignment bl
gap_x 10
gap_y 100

# Graphics settings
draw_shades no
draw_outline no
draw_borders no
draw_graph_borders no

# Text settings
use_xft yes
xftalpha 0
text_buffer_size 2048

uppercase no

default_color grey
TEXT
${voffset 30}${font daniel:size=30}${time %A}${font}${voffset -10}
${voffset 20}${font daniel:size=30}${time %B} ${time %e}${font}${voffset -10}
${voffset 10}${color green}${font daniel:size=45}${time %I:%M%p}${font}${voffset -10}
