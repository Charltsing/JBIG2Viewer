JBIG2Viewer目前并不是一个开源的工具，不开源的原因是它目前还在测试中。
在不久的将来，测试通过之后，我会开源这个项目。

软件说明：
PDF文件中内嵌的图像导出之后的常见图像格式包括：JPG、PNG(PNM)、TIF、JBIG2、JPEG2000，本软件主要用于测试PDF的图像图像提取和替换、JBIG2编解码、图像的二值化漂白等功能。免费使用。

图标栏功能顺序：打开文件，保存文件，二值化、重置原图像、作者网站、二值化参数、二值化的窗口宽度和k值、图像显示缩放

系统需求：
1、Visual C++ 2015-2022 运行库，下载网址 ：
https://aka.ms/vs/17/release/vc_redist.x86.exe
https://aka.ms/vs/17/release/vc_redist.x64.exe
2、.Net Framework 4.7.2，下载网址：
https://dotnet.microsoft.com/zh-cn/download/dotnet-framework/net472

操作说明：
1、图像查看：拖拽PNM(ppm、pgm、pbm)、JBIG2、JP2000、JPG、PNG、TIF、BMP、GIF等支持的图像到软件窗口的图片框。
2、图像二值化：选择算法，拖拽滑块。注意WAN算法宽度超过17之后速度会明显降低。Wolf算法效果可能好于Sauvola。
3、提取PDF图像：拖拽PDF文件到软件窗口的图片框，会在文件同一目录下生成pdfimage目录并提取图像。
4、替换PDF图片：修改提取出来的图片之后，在图标栏的第一个图标，打开PDF文件，软件会自动查找图像目录并替换。
5、保存图像：支持JB2(黑白图)、Pgm(灰度图)，以及其它一些常见格式。
6、图像窗口缩放：在图标栏最右边的数字上滚轮。

JBIG2Viewer is currently not an open source tool, and the reason for not being open source is that it is currently under testing. In the near future, after passing the testing, I will open source this project.

Software Description:

The common image formats after exporting images embedded in PDF files include JPG, PNG, TIF, JBIG2, and JPEG2000. This software is mainly used to test PDF image extraction and replacement, JBIG2 encoding and decoding, image binarization and bleaching, and other functions. Free to use.

Icon bar function sequence: Open file, save file, Binarization, reload original image, author website, binary parameters, windows size and k, image display scaling


System requirements:

1. Visual C++2015-2022 runtime library, download website:
https://aka.ms/vs/17/release/vc_redist.x86.exe
https://aka.ms/vs/17/release/vc_redist.x64.exe

2. . Net Framework 4.7.2, download website:
https://dotnet.microsoft.com/zh-cn/download/dotnet-framework/net472


Operating instructions:

1. Image viewing: Drag and drop PNM(ppm/pgm/pbm)、JBIG2, JP2000, JPG, PNG, TIF, BMP, GIF and other support images into the image box of the software window.
2. Image binarization: Select the algorithm and drag the slider. Note that when the width of the WAN algorithm exceeds 17, the speed will significantly decrease. The Wolf algorithm may perform better than Sauvola.
3. Extract PDF image: Dragging and dropping the PDF file into the image box of the software window will generate a pdfimage directory in the same directory as the file and extract the image.
4. Replace PDF image: After modifying the extracted image, open the PDF file on the first icon in the icon bar, and the software will automatically search for the image directory and replace it.
5. Save images: Supports JB2 (black and white image), Pgm (grayscale image), and other common formats.
6. Image Window Zoom: Scroll on the number at the far right of the icon bar.

