1. io port read and write. ip port read/write in sequece.
2. hardware memeory read/write.
3. CMOS read/write.
4. SMBIOS information read. according to DSP0134.
5. PCI configuration information. Vendor ID, Device ID is get from linux ids data file.
in chinese
1. io端口读写，io端口序列化读写。
2. 物理内存读写。
3. CMOS读写，利用了io端口读写。
3. SMBIOS信息读写，利用了物理内存读写，符合DSP0134。
4. PCI配置寄存器读写。Vendor ID，Device ID取自linux ids数据文件。