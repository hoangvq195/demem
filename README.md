# demem

### Description
demem is a simple memory library for AutoIt that features:
- Basic memory manipulation
- Easy to use read & write value with the types of: ```int, float, double, word, byte```
- Scan AOB (pattern), value, and string
- Support auto length detection for string read, write & scan
- Scanning faster with the help of the demem.dll library
- Support auto handling access permission error
### Functions
```autoit
	demem_open
	demem_close

	demem_read
	demem_write

	demem_readInt
	demem_readFloat
	demem_readDouble
	demem_readWord
	demem_readByte

	demem_writeInt
	demem_writeFloat
	demem_writeDouble
	demem_writeWord
	demem_writeByte

	demem_readString
	demem_readStringUnicode
	demem_writeString
	demem_writeStringUnicode
	
	demem_getBaseAddress
	demem_getModuleAddress

	demem_dllOpen
	demem_dllClose
	demem_isDllLoaded

	demem_scanAOB
	demem_scanValue
	demem_scanString
	demem_scanStringUTF8
	demem_scanStringUnicode
```
### Remarks
If you don't use the scan funtions, you don't need to use the library demem.dll

### Donation
The project is under development, it still has a lot of features being developed, it's a very big help of your donation to keep it running, please contact me anytime you feel like it!
Discord: [thedemons#8671](https://discord.com/users/269920976236576769)
