Import('rtconfig')
from building import *

src	= Glob('*.c')
group = DefineGroup('sl', src, depend = ['PKG_USING_SL'])
Return('group')
