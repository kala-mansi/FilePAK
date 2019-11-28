# FilePAK
Pack files into one resource

//			PAK File Compression
//
//		Packs any set of files (best used on resource files in a program. Images, sounds, etc.) into one .pak file.
//		Each file is encrypted with the caesar encryption, it's really simple: choose a random value between 0 and 255 and
//		randomly choose to either add or subtract then store those values in the files header. Then whenever you store a
//		file you add or subtract that value to every byte.
//
//		Reminder: char represents a byte

// pak文件压缩
//打包任何一组文件(最好用于程序中的资源文件:图像，声音等)进入一个.pak文件。
//每个文件都用caesar加密，很简单:在0到255之间随机选择一个值
//随机选择添加或删除，然后将这些值存储在文件头中。无论何时存储一个文件, 都对每个字节添加或减去那个值。
//注意:char表示一个字节
