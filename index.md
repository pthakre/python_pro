## Downloader multithreaded

import os
from pySmartDL import SmartDL

url = "https://skdiid.net/dl/l/lOsThkiJ2ggO5QxP/Jqx3SuC1JEE/The.Guilty.2018.1080p.BluRay.x264-%5BYTS.AM%5D.mp4"
dest = "C:\\Downloads\\" # or '~/Downloads/' on linux

obj = SmartDL(url, dest)
obj.start().

