# My personal linux command cheat sheet
## Tmux Cheat Sheet
### Session Commands
``
S: List sessions
 
$: Rename current session
 
D: Detach current session
 
Ctrl+B, and then ?: Display Help page in tmux.
``
### Window Commands
``
C: Create a new window.
,: Rename the current window.
W: List the windows.
N: Move to the next window.
P: Move to the previous window.
0 to 9: Move to the window number specified.
``
### Pane Commands
``
%: Create a horizontal split.
“: Create a vertical split.
H or Left Arrow: Move to the pane on the left.
I or Right Arrow: Move to the pane on the right.
J or Down Arrow: Move to the pane below.
K or Up Arrow: Move to the pane above.
Q: Briefly show pane numbers.
O: Move through panes in order. Each press takes you to the next, until you loop through all of them.
}: Swap the position of the current pane with the next.
{: Swap the position of the current pane with the previous.
X: Close the current pane.
``
## General commands that are just hard to remember
`sudo netstat -tnlp | grep :PORT` (Check for ports being listened on)

`sudo sh -c 'echo 1 > /sys/module/bluetooth/parameters/disable_ertm'` (Enhance Bluetooth compatibility on old kernels)

## Linux framebuffer console key codes
```
sdl fbcon
1	53	# Esc
59	122	# F1
60	120	# F2
61	99	# F3
62	118	# F4
63	96	# F5
64	97	# F6
65	98	# F7
66	100	# F8
67	101	# F9
68	109	# F10
87	103	# F11
88	111	# F12
99	105	# PrintScrn
70	107	# Scroll Lock
119	113	# Pause
41	50	# `
2	18	# 1
3	19	# 2
4	20	# 3
5	21	# 4
6	23	# 5
7	22	# 6
8	26	# 7
9	28	# 8
10	25	# 9
11	29	# 0
12	27	# -
13	24	# =
14	51	# Backspace
110	114	# Insert
102	115	# Home
104	116	# Page Up
69	71	# Num Lock
98	75	# KP /
55	67	# KP *
74	78	# KP -
15	48	# Tab
16	12	# Q
17	13	# W
18	14	# E
19	15	# R
20	17	# T
21	16	# Y
22	32	# U
23	34	# I
24	31	# O
25	35	# P
26	33	# [
27	30	# ]
28	36	# Return
111	117	# Delete
107	119	# End
109	121	# Page Down
71	89	# KP 7
72	91	# KP 8
73	92	# KP 9
78	69	# KP +
58	57	# Caps Lock
30	0	# A
31	1	# S
32	2	# D
33	3	# F
34	5	# G
35	4	# H
36	38	# J
37	40	# K
38	37	# L
39	41	# ;
40	39	# '
75	86	# KP 4
76	87	# KP 5
77	88	# KP 6
42	56	# Shift Left
86	50	# International
44	6	# Z
45	7	# X
46	8	# C
47	9	# V
48	11	# B
49	45	# N
50	46	# M
51	43	# ,
52	47	# .
53	44	# /
54	56	# Shift Right
43	42	# \
103	62	# Cursor Up
79	83	# KP 1
80	84	# KP 2
81	85	# KP 3
96	76	# KP Enter
29	54	# Ctrl Left
125	58	# Logo Left (-> Option)
56	55	# Alt Left (-> Command)
57	49	# Space
100	55	# Alt Right (-> Command)
126	58	# Logo Right (-> Option)
97	54	# Ctrl Right
105	59	# Cursor Left
108	61	# Cursor Down
106	60	# Cursor Right
82	82	# KP 0
83	65	# KP .
```
.
