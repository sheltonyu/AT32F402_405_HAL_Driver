from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32f402_405_acc.c'),
os.path.join(src_path, 'at32f402_405_adc.c'),
os.path.join(src_path, 'at32f402_405_can.c'),
os.path.join(src_path, 'at32f402_405_crc.c'),
os.path.join(src_path, 'at32f402_405_crm.c'),
os.path.join(src_path, 'at32f402_405_debug.c'),
os.path.join(src_path, 'at32f402_405_dma.c'),
os.path.join(src_path, 'at32f402_405_ertc.c'),
os.path.join(src_path, 'at32f402_405_exint.c'),
os.path.join(src_path, 'at32f402_405_flash.c'),
os.path.join(src_path, 'at32f402_405_gpio.c'),
os.path.join(src_path, 'at32f402_405_i2c.c'),
os.path.join(src_path, 'at32f402_405_misc.c'),
os.path.join(src_path, 'at32f402_405_pwc.c'),
os.path.join(src_path, 'at32f402_405_qspi.c'),
os.path.join(src_path, 'at32f402_405_scfg.c'),
os.path.join(src_path, 'at32f402_405_spi.c'),
os.path.join(src_path, 'at32f402_405_tmr.c'),
os.path.join(src_path, 'at32f402_405_usart.c'),
os.path.join(src_path, 'at32f402_405_usb.c'),
os.path.join(src_path, 'at32f402_405_wdt.c'),
os.path.join(src_path, 'at32f402_405_wwdt.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32F402_405_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
