### 环境管理

管理 Python 版本和环境的工具

*   p：非常简单的交互式 python 版本管理工具。[官网](https://github.com/qw3rtman/p)
*   pyenv：简单的 Python 版本管理工具。[官网](https://github.com/yyuu/pyenv)
*   Vex：可以在虚拟环境中执行命令。[官网](https://github.com/sashahart/vex)
*   virtualenv：创建独立 Python 环境的工具。[官网](https://pypi.python.org/pypi/virtualenv)
*   virtualenvwrapper：virtualenv 的一组扩展。[官网](https://pypi.python.org/pypi/virtualenvwrapper)
*   buildout：在隔离环境初始化后使用声明性配置管理。[官网](http://www.buildout.org/en/latest)

### 包管理

管理包和依赖的工具。

*   pip：Python 包和依赖关系管理工具。[官网](https://pip.pypa.io/)
*   pip-tools：保证 Python 包依赖关系更新的一组工具。[官网](https://github.com/nvie/pip-tools)
*   pipenv：Python 官方推荐的新一代包管理工具。[官网](https://github.com/pypa/pipenv)
*   poetry: 可完全取代 setup.py 的包管理工具。[官网](https://poetry.eustace.io)
*   conda：跨平台，Python 二进制包管理工具。[官网](https://github.com/conda/conda/)
*   Curdling：管理 Python 包的命令行工具。[官网](http://clarete.li/curdling/)
*   wheel：Python 分发的新标准，意在取代 eggs。[官网](http://pythonwheels.com/)

### 包仓库

本地 PyPI 仓库服务和代理。

*   [warehouse](https://pypi.org/)：下一代 PyPI。[官网](https://github.com/pypa/warehouse)
*   bandersnatch：PyPA 提供的 PyPI 镜像工具。[官网](https://bitbucket.org/pypa/bandersnatch)
*   devpi：PyPI 服务和打包/测试/分发工具。[官网](http://doc.devpi.net/)
*   localshop：本地 PyPI 服务（自定义包并且自动对 PyPI 镜像）。[官网](https://github.com/mvantellingen/localshop)

### 分发

打包为可执行文件以便分发。

*   PyInstaller：将 Python 程序转换成独立的执行文件（跨平台）。[官网](https://github.com/pyinstaller/pyinstaller)
*   cx_Freeze：将python程序转换为带有一个动态链接库的可执行文件。[官网](https://cx-freeze.readthedocs.io/en/latest/index.html)
*   dh-virtualenv：构建并将 virtualenv 虚拟环境作为一个 Debian 包来发布。[官网](http://dh-virtualenv.readthedocs.org/)
*   Nuitka：将脚本、模块、包编译成可执行文件或扩展模块。[官网](http://nuitka.net/)
*   py2app：将 Python 脚本变为独立软件包（Mac OS X）。[官网](http://pythonhosted.org/py2app/)
*   py2exe：将 Python 脚本变为独立软件包（Windows）。[官网](http://www.py2exe.org/)
*   pynsist：一个用来创建 Windows 安装程序的工具，可以在安装程序中打包 Python 本身。[官网](http://pynsist.readthedocs.org/)

### 构建工具

将源码编译成软件。

*   buildout：一个构建系统，从多个组件来创建，组装和部署应用。[官网](http://www.buildout.org/)
*   BitBake：针对嵌入式 Linux 的类似 make 的构建工具。[官网](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html)
*   fabricate：对任何语言自动找到依赖关系的构建工具。[官网](https://code.google.com/archive/p/fabricate)
*   PlatformIO：多平台命令行构建工具。[官网](https://github.com/platformio/platformio)
*   PyBuilder：纯 Python 实现的持续化构建工具。[官网](https://github.com/pybuilder/pybuilder)
*   SCons：软件构建工具。[官网](http://www.scons.org/)

### 交互式解析器

交互式 Python 解析器。

*   IPython：功能丰富的工具，非常有效的使用交互式 Python。[官网](https://github.com/ipython/ipython)
*   [bpython](http://hao.importnew.com/bpython/)：界面丰富的 Python 解析器。[官网](http://bpython-interpreter.org/)
*   ptpython：高级交互式 Python 解析器， 构建于 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) 之上。[官网](https://github.com/jonathanslenders/ptpython)

### 文件

文件管理和 MIME（多用途的网际邮件扩充协议）类型检测。

*   aiofiles：基于 asyncio，提供文件异步操作。[官网](https://github.com/Tinche/aiofiles)
*   imghdr：（Python 标准库）检测图片类型。[官网](https://docs.python.org/2/library/imghdr.html)
*   mimetypes：（Python 标准库）将文件名映射为 MIME 类型。[官网](https://docs.python.org/2/library/mimetypes.html)
*   path.py：对 os.path 进行封装的模块。[官网](https://github.com/jaraco/path.py)
*   pathlib：（Python3.4+ 标准库）跨平台的、面向对象的路径操作库。[官网](https://pathlib.readthedocs.org/en/pep428/)
*   python-magic：文件类型检测的第三方库 libmagic 的 Python 接口。[官网](https://github.com/ahupp/python-magic)
*   Unipath：用面向对象的方式操作文件和目录。[官网](https://github.com/mikeorr/Unipath)
*   watchdog：管理文件系统事件的 API 和 shell 工具。[官网](https://github.com/gorakhargosh/watchdog)

### 日期和时间

操作日期和时间的类库。

*   arrow：更好的 Python 日期时间操作类库。[官网](https://github.com/crsmithdev/arrow)
*   Chronyk：Python 3 的类库，用于解析手写格式的时间和日期。[官网](https://github.com/KoffeinFlummi/Chronyk)
*   dateutil：Python datetime 模块的扩展。[官网](https://pypi.python.org/pypi/python-dateutil)
*   delorean：解决 Python 中有关日期处理的棘手问题的库。[官网](https://github.com/myusuf3/delorean/)
*   maya：人性化的时间处理库。[官网](https://github.com/kennethreitz/maya)
*   moment：一个用来处理时间和日期的 Python 库。灵感来自于 Moment.js。[官网](https://github.com/zachwill/moment)
*   pendulum：一个比 arrow 更具有明确的，可预测的行为的时间操作库。[官网](https://github.com/sdispater/pendulum)
*   PyTime：一个简单易用的 Python 模块，用于通过字符串来操作日期/时间。[官网](https://github.com/shinux/PyTime)
*   pytz：现代以及历史版本的世界时区定义。将时区数据库引入 Python。[官网](https://launchpad.net/pytz)
*   when.py：提供用户友好的函数来帮助用户进行常用的日期和时间操作。[官网](https://github.com/dirn/When.py)

### 文本处理

用于解析和操作文本的库。

*   通用
    *   [chardet](http://hao.importnew.com/chardet/)：字符编码检测器，兼容 Python2 和 Python3。[官网](https://github.com/chardet/chardet)
    *   difflib：(Python 标准库)帮助我们进行差异化比较。[官网](https://docs.python.org/2/library/difflib.html)
    *   ftfy：让 Unicode 文本更完整更连贯。[官网](https://github.com/LuminosoInsight/python-ftfy)
    *   fuzzywuzzy：模糊字符串匹配。[官网](https://github.com/seatgeek/fuzzywuzzy)
    *   Levenshtein：快速计算编辑距离以及字符串的相似度。[官网](https://github.com/ztane/python-Levenshtein/)
    *   pangu.py：在中日韩语字符和数字字母之间添加空格。[官网](https://github.com/vinta/pangu.py)
    *   pypinyin：汉字拼音转换工具 Python 版。[官网](https://github.com/mozillazg/python-pinyin)
    *   shortuuid：一个生成器库，用以生成简洁的，明白的，URL 安全的 UUID。[官网](https://github.com/stochastic-technologies/shortuuid)
    *   [simplejson](https://github.com/simplejson/simplejson)：Python 的 JSON 编码、解码器。[官网](https://simplejson.readthedocs.io/en/latest/)
    *   unidecode：Unicode 文本的 ASCII 转换形式 。[官网](https://pypi.python.org/pypi/Unidecode)
    *   uniout：打印可读的字符，而不是转义的字符串。[官网](https://github.com/moskytw/uniout)
    *   xpinyin：一个用于把汉字转换为拼音的库。[官网](https://github.com/lxneng/xpinyin)
    *   yfiglet-figlet：[pyfiglet -figlet](https://github.com/pwaller/pyfiglet) 的 Python 实现。
    *   flashtext: 一个高效的文本查找替换库。[官网](https://github.com/vi3k6i5/flashtext)
*   Slug 化
    *   awesome-slugify：一个 Python slug 化库，可以保持 Unicode。[官网](https://github.com/dimka665/awesome-slugify)
    *   python-slugify：Python slug 化库，可以把 unicode 转化为 ASCII。[官网](https://github.com/un33k/python-slugify)
    *   unicode-slugify：一个 slug 工具，可以生成 unicode slugs ,需要依赖 Django 。[官网](https://github.com/mozilla/unicode-slugify)
*   解析器
    *   phonenumbers：解析，格式化，储存，验证电话号码。[官网](https://github.com/daviddrysdale/python-phonenumbers)
    *   PLY：lex 和 yacc 解析工具的 Python 实现。[官网](http://www.dabeaz.com/ply/)
    *   Pygments：通用语法高亮工具。[官网](http://pygments.org/)
    *   pyparsing：生成通用解析器的框架。[官网](http://pyparsing.wikispaces.com/)
    *   python-nameparser：把一个人名分解为几个独立的部分。[官网](https://github.com/derek73/python-nameparser)
    *   python-user-agents：浏览器 user agent 解析器。[官网](https://github.com/selwin/python-user-agents)
    *   sqlparse：一个无验证的 SQL 解析器。[官网](https://sqlparse.readthedocs.org/en/latest/)

### 特殊文本格式处理

一些用来解析和操作特殊文本格式的库。

*   通用
    *   tablib：一个用来处理中表格数据的模块。[官网](https://github.com/kennethreitz/tablib)
*   Office
    *   Marmir：把输入的 Python 数据结构转换为电子表单。[官网](https://github.com/brianray/mm)
    *   openpyxl：一个用来读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库。[官网](https://openpyxl.readthedocs.org/en/latest/)
    *   pyexcel：一个提供统一 API，用来读写，操作 Excel 文件的库。[官网](https://github.com/pyexcel/pyexcel)
    *   python-docx：读取，查询以及修改 Microsoft Word 2007/2008 docx 文件。[官网](https://github.com/python-openxml/python-docx)
    *   relatorio：模板化 OpenDocument 文件。[官网](http://relatorio.tryton.org/)
    *   unoconv：在 LibreOffice/OpenOffice 支持的任意文件格式之间进行转换。[官网](https://github.com/dagwieers/unoconv)
    *   XlsxWriter：一个用于创建 Excel .xlsx 文件的 Python 模块。[官网](https://xlsxwriter.readthedocs.org/en/latest/)
    *   xlwings：一个使得在 Excel 中方便调用 Python 的库（反之亦然），基于 BSD 协议。[官网](http://xlwings.org/)
    *   [xlwt](http://hao.importnew.com/xlwt/)：读写 Excel 文件的数据和格式信息。[官网](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd)
*   PDF
    *   PDFMiner：一个用于从 PDF 文档中抽取信息的工具。[官网](https://github.com/euske/pdfminer)
    *   PyPDF2：一个可以分割，合并和转换 PDF 页面的库。[官网](https://github.com/mstamy2/PyPDF2)
    *   ReportLab：快速创建富文本 PDF 文档。[官网](http://www.reportlab.com/opensource/)
*   Markdown
    *   Mistune：快速并且功能齐全的纯 Python 实现的 Markdown 解析器。[官网](https://github.com/lepture/mistune)
    *   Python-Markdown：John Gruber’s Markdown 的 Python 版实现。[官网](https://github.com/waylan/Python-Markdown)
    *   Python-Markdown2：纯 Python 实现的 Markdown 解析器，比 Python-Markdown 更快，更准确，可扩展。[官网](https://github.com/trentm/python-markdown2)
*   YAML
    *   PyYAML：Python 版本的 YAML 解析器。[官网](http://pyyaml.org/)
*   CSV
    *   csvkit：用于转换和操作 CSV 的工具。[官网](https://github.com/wireservice/csvkit)
*   Archive
    *   unp：一个用来方便解包归档文件的命令行工具。[官网](https://github.com/mitsuhiko/unp)



### 文档

用以生成项目文档的库。

*   [Sphinx](http://hao.importnew.com/sphinx/)：Python 文档生成器。[官网](http://www.sphinx-doc.org/en/latest/)
*   awesome-sphinxdoc：[官网](https://github.com/yoloseem/awesome-sphinxdoc)
*   MkDocs：对 Markdown 友好的文档生成器。[官网](http://www.mkdocs.org/)
*   pdoc：一个可以替换 Epydoc 的库，可以自动生成 Python 库的 API 文档。[官网](https://github.com/BurntSushi/pdoc)
*   Pycco：文学编程（literate-programming）风格的文档生成器。[官网](https://github.com/pycco-docs/pycco)
*   readthedocs：一个基于 Sphinx/MkDocs 的在线文档托管系统，对开源项目免费开放使用。[官网](https://github.com/rtfd/readthedocs.org/)

### 配置

用来保存和解析配置的库。

*   config：[logging](https://docs.python.org/2/library/logging.html) 模块作者写的分级配置模块。[官网](https://www.red-dove.com/config-doc/)
*   ConfigObj：INI 文件解析器，带验证功能。[官网](http://www.voidspace.org.uk/python/configobj.html)
*   ConfigParser：(Python 标准库) INI 文件解析器。[官网](https://docs.python.org/2/library/configparser.html)
*   profig：通过多种格式进行配置，具有数值转换功能。[官网](http://profig.readthedocs.org/en/default/)
*   python-decouple：将设置和代码完全隔离。[官网](https://github.com/henriquebastos/python-decouple)

### 命令行工具

用于创建命令行程序的库。

*   命令行程序开发
    *   asciimatics：跨平台，全屏终端包（即鼠标/键盘输入和彩色，定位文本输出），完整的复杂动画和特殊效果的高级 API。[官网](https://github.com/peterbrittain/asciimatics)
    *   cement：Python 的命令行程序框架。[官网](http://builtoncement.com/)
    *   click：一个通过组合的方式来创建精美命令行界面的包。[官网](http://click.pocoo.org/dev/)
    *   cliff：一个用于创建命令行程序的框架，可以创建具有多层命令的命令行程序。[官网](http://docs.openstack.org/developer/cliff/)
    *   clint：Python 命令行程序工具。[官网](https://github.com/kennethreitz/clint)
    *   colorama：跨平台彩色终端文本。[官网](https://pypi.python.org/pypi/colorama)
    *   docopt：Python 风格的命令行参数解析器。[官网](http://docopt.org/)
    *   Gooey：一条命令，将命令行程序变成一个 GUI 程序。[官网](https://github.com/chriskiehl/Gooey)
    *   python-prompt-toolkit：一个用于构建强大的交互式命令行程序的库。[官网](https://github.com/jonathanslenders/python-prompt-toolkit)
    *   python-fire：Google 出品的一个基于 Python 类的构建命令行界面的库。[官网](https://github.com/google/python-fire)
    *   [Pythonpy](http://hao.importnew.com/pythonpy/)：在命令行中直接执行任何 Python 指令。[官网](https://github.com/Russell91/pythonpy/wiki)
*   生产力工具
    *   aws-cli：Amazon Web Services 的通用命令行界面。[官网](https://github.com/aws/aws-cli)
    *   bashplotlib：在终端中进行基本绘图。[官网](https://github.com/glamp/bashplotlib)
    *   caniusepython3：判断是哪个项目妨碍你你移植到 Python3。[官网](https://github.com/brettcannon/caniusepython3)
    *   cookiecutter：从 cookiecutters（项目模板）创建项目的一个命令行工具。[官网](https://github.com/audreyr/cookiecutter)
    *   doitlive：一个用来在终端中进行现场演示的工具。[官网](https://github.com/sloria/doitlive)
    *   pyftpdlib：一个速度极快和可扩展的 Python FTP 服务库。[官网](https://github.com/giampaolo/pyftpdlib)
    *   howdoi：通过命令行获取即时的编程问题解答。[官网](https://github.com/gleitz/howdoi)
    *   httpie：一个命令行 HTTP 客户端，cURL 的替代品，易用性更好。[官网](https://github.com/jkbrzt/httpie)
    *   PathPicker：从 bash 输出中选出文件。[官网](https://github.com/facebook/PathPicker)
    *   percol：向 UNIX shell 传统管道概念中加入交互式选择功能。[官网](https://github.com/mooz/percol)
    *   SAWS：一个加强版的 AWS 命令行。[官网](https://github.com/donnemartin/saws)
    *   thefuck：修正你之前的命令行指令。[官网](https://github.com/nvbn/thefuck)
    *   mycli：一个 MySQL 命令行客户端，具有自动补全和语法高亮功能。[官网](https://github.com/dbcli/mycli)
    *   pgcli：Postgres 命令行工具，具有自动补全和语法高亮功能。[官网](https://github.com/dbcli/pgcli)
    *   try：一个从来没有更简单的命令行工具，用来试用 python 库。[官网](https://github.com/timofurrer/try)

### 下载器

用来进行下载的库.

*   s3cmd：一个用来管理 Amazon S3 和 CloudFront 的命令行工具。[官网](https://github.com/s3tools/s3cmd)
*   s4cmd：超级 S3 命令行工具，性能更加强劲。[官网](https://github.com/bloomreach/s4cmd)
*   you-get：一个 YouTube/Youku/Niconico 视频下载器，使用 Python3 编写。[官网](https://www.soimort.org/you-get/)
*   youtube-dl：一个小巧的命令行程序，用来下载 YouTube 视频。[官网](http://rg3.github.io/youtube-dl/)

### 图像处理

用来操作图像的库.

*   [pillow](http://hao.importnew.com/pillow/)：Pillow 是一个更加易用版的 [PIL](http://www.pythonware.com/products/pil/)。[官网](http://pillow.readthedocs.org/en/latest/)
*   hmap：图像直方图映射。[官网](https://github.com/rossgoodwin/hmap)
*   imgSeek：一个使用视觉相似性搜索一组图片集合的项目。[官网](https://sourceforge.net/projects/imgseek/)
*   nude.py：裸体检测。[官网](https://github.com/hhatto/nude.py)
*   pyBarcode：不借助 PIL 库在 Python 程序中生成条形码。[官网](https://pythonhosted.org/pyBarcode/)
*   pygram：类似 Instagram 的图像滤镜。[官网](https://github.com/ajkumar25/pygram)
*   python-qrcode：一个纯 Python 实现的二维码生成器。[官网](https://github.com/lincolnloop/python-qrcode)
*   Quads：基于四叉树的计算机艺术。[官网](https://github.com/fogleman/Quads)
*   scikit-image：一个用于（科学）图像处理的 Python 库。[官网](http://scikit-image.org/)
*   thumbor：一个小型图像服务，具有剪裁，尺寸重设和翻转功能。[官网](https://github.com/thumbor/thumbor)
*   wand：[MagickWand](http://www.imagemagick.org/script/magick-wand.php)的 Python 绑定。MagickWand 是 ImageMagick 的 C API 。[官网](https://github.com/dahlia/wand)
*   face_recognition：简单易用的 python 人脸识别库。[官网](https://github.com/ageitgey/face_recognition)

### OCR

光学字符识别库。

*   pyocr：Tesseract 和 Cuneiform 的一个封装(wrapper)。[官网](https://github.com/jflesch/pyocr)
*   [pytesseract](http://hao.importnew.com/pytesseract/)：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的另一个封装(wrapper)。[官网](https://github.com/madmaze/pytesseract)
*   python-tesseract：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的一个包装类。

### 音频

用来操作音频的库

*   audiolazy：Python 的数字信号处理包。[官网](https://github.com/danilobellini/audiolazy) 
*   audioread：交叉库 (GStreamer + Core Audio + MAD + FFmpeg) 音频解码。[官网](https://github.com/beetbox/audioread)
*   beets：一个音乐库管理工具及 [MusicBrainz](https://musicbrainz.org/) 标签添加工具。[官网](http://beets.io/)
*   dejavu：音频指纹提取和识别。[官网](https://github.com/worldveil/dejavu)
*   [django-elastic-transcoder](http://hao.importnew.com/django-elastic-transcoder/)：Django + [Amazon Elastic Transcoder](http://aws.amazon.com/elastictranscoder/)。[官网](https://github.com/StreetVoice/django-elastic-transcoder)
*   eyeD3：一个用来操作音频文件的工具，具体来讲就是包含 ID3 元信息的 MP3 文件。[官网](http://eyed3.nicfit.net/)
*   id3reader：一个用来读取 MP3 元数据的 Python 模块。[官网](http://nedbatchelder.com/code/modules/id3reader.py)
*   m3u8：一个用来解析 m3u8 文件的模块。[官网](https://github.com/globocom/m3u8)
*   mutagen：一个用来处理音频元数据的 Python 模块。[官网](https://bitbucket.org/lazka/mutagen)
*   pydub：通过简单、简洁的高层接口来操作音频文件。[官网](https://github.com/jiaaro/pydub)
*   pyechonest：[Echo Nest](http://developer.echonest.com/) API 的 Python 客户端。[官网](https://github.com/echonest/pyechonest)
*   talkbox：一个用来处理演讲/信号的 Python 库。[官网](http://scikits.appspot.com/talkbox)
*   TimeSide：开源 web 音频处理框架。[官网](https://github.com/Parisson/TimeSide)
*   tinytag：一个用来读取 MP3, OGG, FLAC 以及 Wave 文件音乐元数据的库。[官网](https://github.com/devsnd/tinytag)
*   mingus：一个高级音乐理论和曲谱包，支持 MIDI 文件和回放功能。[官网](http://bspaans.github.io/python-mingus/)

### Video

用来操作视频和 GIF 的库。

*   moviepy：一个用来进行基于脚本的视频编辑模块，适用于多种格式，包括动图 GIFs。[官网](http://zulko.github.io/moviepy/)
*   scikit-video：SciPy 视频处理常用程序。[官网](https://github.com/aizvorski/scikit-video)

### 地理位置

地理编码地址以及用来处理经纬度的库。

*   GeoDjango：世界级地理图形 web 框架。[官网](https://docs.djangoproject.com/en/dev/ref/contrib/gis/)
*   GeoIP：MaxMind GeoIP Legacy 数据库的 Python API。[官网](https://github.com/maxmind/geoip-api-python)
*   geojson：GeoJSON 的 Python 绑定及工具。[官网](https://github.com/frewsxcv/python-geojson)
*   geopy：Python 地址编码工具箱。[官网](https://github.com/geopy/geopy)
*   GeoIP2：GeoIP2 Webservice 客户端与数据库 Python API。[官网](https://github.com/maxmind/GeoIP2-python)
*   django-countries：一个 Django 应用程序，提供用于表格的国家选择功能，国旗图标静态文件以及模型中的国家字段。[官网](https://github.com/SmileyChris/django-countries)
*   最全最新中国省，市，地区json及sql数据。  [官网](https://github.com/wecatch/china_regions)
*   

### HTTP

使用 HTTP 的库。
*   aiohttp：基于 asyncio 的异步 HTTP 网络库。[官网](https://github.com/aio-libs/aiohttp)
*   requests：人性化的 HTTP 请求库。[官网](http://docs.python-requests.org/en/latest/)
*   grequests：requests 库 + gevent ，用于异步 HTTP 请求.[官网](https://github.com/kennethreitz/grequests)
*   httplib2：全面的 HTTP 客户端库。[官网](https://github.com/jcgregorio/httplib2)
*   treq：类似 requests 的 Python API 构建于 Twisted HTTP 客户端之上。[官网](https://github.com/twisted/treq)
*   urllib3：一个具有线程安全连接池，支持文件 post，清晰友好的 HTTP 库。[官网](https://github.com/shazow/urllib3)

### 数据库

Python 实现的数据库。

*   pickleDB：一个简单，轻量级键值储存数据库。[官网](https://pythonhosted.org/pickleDB/)
*   PipelineDB：流式 SQL 数据库。[官网](https://www.pipelinedb.com/)
*   TinyDB：一个微型的，面向文档型数据库。[官网](https://github.com/msiemens/tinydb)
*   ZODB：一个 Python 原生对象数据库。一个键值和对象图数据库。[官网](http://www.zodb.org/en/latest/)

### 数据库驱动

用来连接和操作数据库的库。

*   MySQL：[awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/) 系列
    *   aiomysql：基于 asyncio 的异步 MySQL 数据库操作库。[官网](https://github.com/aio-libs/aiomysql)
    *   mysql-python：Python 的 MySQL 数据库连接器。[官网](https://sourceforge.net/projects/mysql-python/)
    *   ysqlclient：[mysql-python](https://github.com/PyMySQL/mysqlclient-python) 分支，支持 Python 3。
    *   oursql：一个更好的 MySQL 连接器，支持原生预编译指令和 BLOBs。[官网](https://pythonhosted.org/oursql/)
    *   PyMySQL：纯 Python MySQL 驱动，兼容 mysql-python。[官网](https://github.com/PyMySQL/PyMySQL)
*   PostgreSQL
    *   psycopg2：Python 中最流行的 PostgreSQL 适配器。[官网](http://initd.org/psycopg/)
    *   queries：psycopg2 库的封装，用来和 PostgreSQL 进行交互。[官网](https://github.com/gmr/queries)
    *   txpostgres：基于 Twisted 的异步 PostgreSQL 驱动。[官网](http://txpostgres.readthedocs.org/en/latest/)
*   其他关系型数据库
    *   apsw：另一个 Python SQLite 封装。[官网](http://rogerbinns.github.io/apsw/)
    *   dataset：在数据库中存储 Python 字典
    *   pymssql：一个简单的 Microsoft SQL Server 数据库接口。[官网](http://www.pymssql.org/en/latest/)
*   NoSQL 数据库
    *   asyncio-redis：基于 asyncio 的 redis 客户端 (PEP 3156)。[官网](https://github.com/jonathanslenders/asyncio-redis)
    *   cassandra-python-driver：Cassandra 的 Python 驱动。[官网](https://github.com/datastax/python-driver)
    *   HappyBase：一个为 Apache HBase 设计的，对开发者友好的库。[官网](http://happybase.readthedocs.org/en/latest/)
    *   Plyvel：一个快速且功能丰富的 LevelDB 的 Python 接口。[官网](https://plyvel.readthedocs.org/en/latest/)
    *   py2neo：Neo4j restful 接口的 Python 封装客户端。[官网](http://py2neo.org/2.0/)
    *   pycassa：Cassandra 的 Python Thrift 驱动。[官网](https://github.com/pycassa/pycassa)
    *   PyMongo：MongoDB 的官方 Python 客户端。[官网](https://docs.mongodb.org/ecosystem/drivers/python/)
    *   redis-py：Redis 的 Python 客户端。[官网](https://github.com/andymccurdy/redis-py)
    *   telephus：基于 Twisted 的 Cassandra 客户端。[官网](https://github.com/driftx/Telephus)
    *   txRedis：基于 Twisted 的 Redis 客户端。[官网](https://github.com/deldotdr/txRedis)

### ORM

实现对象关系映射或数据映射技术的库。

*   关系型数据库
    *   Django Models：Django 的一部分。[官网](https://docs.djangoproject.com/en/dev/topics/db/models/)
    *   SQLAlchemy：Python SQL 工具以及对象关系映射工具。[官网](http://www.sqlalchemy.org/)
        *   [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) 系列
    *   [Peewee](http://hao.importnew.com/peewee/)：一个小巧，富有表达力的 ORM。[官网](https://github.com/coleifer/peewee)
    *   PonyORM：提供面向生成器的 SQL 接口的 ORM。[官网](https://ponyorm.com/)
    *   python-sql：编写 Python 风格的 SQL 查询。[官网](https://pypi.python.org/pypi/python-sql)
*   NoSQL 数据库
    *   django-mongodb-engine：Django MongoDB 后端。[官网](https://github.com/django-nonrel/mongodb-engine)
    *   PynamoDB：[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) 的一个 Python 风格接口。[官网](https://github.com/jlafon/PynamoDB)
    *   flywheel：Amazon DynamoDB 的对象映射工具。[官网](https://github.com/mathcamp/flywheel)
    *   MongoEngine：一个 Python 对象文档映射工具，用于 MongoDB。[官网](http://mongoengine.org/)
    *   hot-redis：为 Redis 提供 Python 丰富的数据类型。[官网](https://github.com/stephenmcd/hot-redis)
    *   redisco：一个 Python 库，提供可以持续存在在 Redis 中的简单模型和容器。[官网](https://github.com/kiddouk/redisco)
*   其他
    *   butterdb：Google Drive 电子表格的 Python ORM。[官网](https://github.com/Widdershin/butterdb)

### Web 框架

全栈 Web 框架。

*   [Django](http://hao.importnew.com/django/)：Python 界最流行的 web 框架。[官网](https://www.djangoproject.com/)
    *   [awesome-django](https://gitlab.com/rosarior/awesome-django) 系列
*   [Flask](http://hao.importnew.com/flask/)：一个 Python 微型框架。[官网](http://flask.pocoo.org/)
    *   [awesome-flask](https://github.com/humiaozuzu/awesome-flask) 系列
*   pyramid：一个小巧，快速，接地气的开源 Python web 框架。
    *   [awesome-pyramid](https://github.com/uralbash/awesome-pyramid) 系列
*   [Bottle](http://hao.importnew.com/bottle/)：一个快速小巧，轻量级的 WSGI 微型 web 框架。[官网](http://bottlepy.org/docs/dev/index.html)
*   CherryPy：一个极简的 Python web 框架，服从 HTTP/1.1 协议且具有 WSGI 线程池。[官网](http://www.cherrypy.org/)
*   TurboGears：一个可以扩展为全栈解决方案的微型框架。[官网](http://www.turbogears.org/)
*   [web.py](http://hao.importnew.com/python-webpy/)：一个 Python 的 web 框架，既简单，又强大。[官网](http://webpy.org/)
*   web2py：一个全栈 web 框架和平台，专注于简单易用。[官网](http://www.web2py.com/)
*   [Tornado](http://hao.importnew.com/tornado/)：一个 web 框架和异步网络库。[官网](http://www.tornadoweb.org/en/latest/)
*   sanic：基于 Python3.5+ 的异步网络框架。[官网](https://github.com/channelcat/sanic/)
*   starlette: 一款轻量级，高性能的 ASGI 框架  🌟。 [官网](https://www.starlette.io/)



### 队列

处理事件以及任务队列的库。

*   celery：一个异步任务队列/作业队列，基于分布式消息传递。[官网](http://www.celeryproject.org/)
*   huey：小型多线程任务队列。[官网](https://github.com/coleifer/huey)
*   [mrq](http://hao.importnew.com/mrq/)：Mr. Queue -一个 Python 的分布式 worker 任务队列， 使用 Redis 和 gevent。[官网](https://github.com/pricingassistant/mrq)
*   rq：简单的 Python 作业队列。[官网](http://python-rq.org/)
*   simpleq：一个简单的，可无限扩张的，基于亚马逊 SQS 的队列。[官网](https://github.com/rdegges/simpleq)

### 电子邮件

用来发送和解析电子邮件的库。

*   django-celery-ses：带有 AWS SES 和 Celery 的 Django email 后端。[官网](https://github.com/StreetVoice/django-celery-ses)
*   envelopes：供人类使用的电子邮件库。[官网](http://tomekwojcik.github.io/envelopes/)
*   flanker：一个 email 地址和 Mime 解析库。[官网](https://github.com/mailgun/flanker)
*   imbox：Python IMAP 库。[官网](https://github.com/martinrusev/imbox)
*   inbox.py：Python SMTP 服务器。[官网](https://github.com/kennethreitz/inbox.py)
*   inbox：一个开源电子邮件工具箱。[官网](https://github.com/nylas/sync-engine)
*   lamson：Python 风格的 SMTP 应用服务器。[官网](https://github.com/zedshaw/lamson)
*   mailjet：Mailjet API 实现，用来提供批量发送邮件，统计等功能。[官网](https://github.com/WoLpH/mailjet)
*   marrow.mailer：高性能可扩展邮件分发框架。[官网](https://github.com/marrow/mailer)
*   modoboa：一个邮件托管和管理平台，具有现代的、简约的 Web UI。[官网](https://github.com/tonioo/modoboa)
*   pyzmail：创建，发送和解析电子邮件。[官网](http://www.magiksys.net/pyzmail/)
*   Talon：Mailgun 库，用来抽取信息和签名。[官网](https://github.com/mailgun/talon)
*   yagmail：yagmail是一个GMAIL / SMTP客户端，旨在使其尽可能简单地发送电子邮件。[官网](https://pypi.org/project/yagmail/)

### 国际化

用来进行国际化的库。

*   Babel：一个 Python 的国际化库。[官网](http://babel.pocoo.org/en/latest/)
*   Korean：一个韩语词态库。[官网](https://korean.readthedocs.org/en/latest/)

### HTML 处理

处理 HTML 和 XML 的库。

*   BeautifulSoup：以 Python 风格的方式来对 HTML 或 XML 进行迭代，搜索和修改。[官网](http://www.crummy.com/software/BeautifulSoup/bs4/doc/)
*   bleach：一个基于白名单的 HTML 清理和文本链接库。[官网](http://bleach.readthedocs.org/en/latest/)
*   cssutils：一个 Python 的 CSS 库。[官网](https://pypi.python.org/pypi/cssutils/)
*   html5lib：一个兼容标准的 HTML 文档和片段解析及序列化库。[官网](https://github.com/html5lib/html5lib-python)
*   lxml：一个非常快速，简单易用，功能齐全的库，用来处理 HTML 和 XML。[官网](http://lxml.de/)
*   MarkupSafe：为 Python 实现 XML/HTML/XHTML 标记安全字符串。[官网](https://github.com/pallets/markupsafe)
*   pyquery：一个解析 HTML 的库，类似 jQuery。[官网](https://github.com/gawel/pyquery)
*   requests-html：人性化的，Pythonic 的 HTML 解析库。[官网](https://github.com/kennethreitz/requests-html)
*   untangle：将 XML 文档转换为 Python 对象，使其可以方便的访问。[官网](https://github.com/stchris/untangle)
*   xhtml2pdf：HTML/CSS 转 PDF 工具。[官网](https://github.com/xhtml2pdf/xhtml2pdf)
*   xmltodict：像处理 JSON 一样处理 XML。[官网](https://github.com/martinblech/xmltodict)

爬取网络站点的库

*   Scrapy：一个快速高级的屏幕爬取及网页采集框架。[官网](http://scrapy.org/)
*   ScrapydWeb：一个用于 Scrapyd 集群管理的全功能 web UI，支持 Scrapy 日志分析和可视化，自动打包，定时器任务和邮件通知等特色功能。[官网](https://github.com/my8100/scrapydweb)
*   cola：一个分布式爬虫框架。[官网](https://github.com/chineking/cola)
*   Demiurge：基于 PyQuery 的爬虫微型框架。[官网](https://github.com/matiasb/demiurge)
*   feedparser：通用 feed 解析器。[官网](http://pythonhosted.org/feedparser/)
*   Grab：站点爬取框架。[官网](http://grablib.org/)
*   MechanicalSoup：用于自动和网络站点交互的 Python 库。[官网](https://github.com/hickford/MechanicalSoup)
*   portia：Scrapy 可视化爬取。[官网](https://github.com/scrapinghub/portia)
*   pyspider：一个强大的爬虫系统。[官网](https://github.com/binux/pyspider)
*   RoboBrowser：一个简单的，Python 风格的库，用来浏览网站，而不需要一个独立安装的浏览器。[官网](https://github.com/jmcarp/robobrowser)

### 网页内容提取

用于进行网页内容提取的库。

*   Haul：一个可以扩展的图像爬取工具。[官网](https://github.com/vinta/Haul)
*   html2text：将 HTML 转换为 Markdown 格式文本。[官网](https://github.com/Alir3z4/html2text)
*   lassie：人性化的网页内容检索库。[官网](https://github.com/michaelhelmick/lassie)
*   micawber：一个小型网页内容提取库，用来从 URLs 提取富内容。[官网](https://github.com/coleifer/micawber) 
*   [newspaper](http://hao.importnew.com/python-newspaper/)：使用 Python 进行新闻提取，文章提取以及内容策展。[官网](https://github.com/codelucas/newspaper)
*   opengraph：一个用来解析开放内容协议(Open Graph Protocol)的 Python 模块。[官网](https://github.com/erikriver/opengraph)
*   [python-goose](http://hao.importnew.com/python-goose/)：HTML 内容/文章提取器(python2)。[官网](https://github.com/grangier/python-goose)
*   [goose3](http://goose3.readthedocs.io/en/latest/index.html):  HTML 内容/文章提取器(python3)。[官网](https://github.com/goose3/goose3)
*   python-readability：arc90 公司 readability 工具的 Python 高速端口。[官网](https://github.com/buriy/python-readability)
*   sanitize：为杂乱的数据世界带来调理性。[官网](https://github.com/Alir3z4/python-sanitize)
*   sumy：一个为文本文件和 HTML 页面进行自动摘要的模块。[官网](https://github.com/miso-belica/sumy)
*   textract：从任何格式的文档中提取文本，Word，PowerPoint，PDFs 等等。[官网](https://github.com/deanmalmgren/textract)



### 进程

操作系统进程启动及通信库。

*   envoy：比 Python [subprocess](https://docs.python.org/2/library/subprocess.html) 模块更人性化。[官网](https://github.com/kennethreitz/envoy)
*   sarge：另一 种 subprocess 模块的封装。[官网](http://sarge.readthedocs.org/en/latest/)
*   sh：一个完备的 subprocess 替代库。[官网](https://github.com/amoffat/sh)

### 并发和并行

用以进行并发和并行操作的库。

*   multiprocessing：(Python 标准库) 基于进程的“线程”接口。[官网](https://docs.python.org/2/library/multiprocessing.html)
*   threading：(Python 标准库)更高层的线程接口。[官网](https://docs.python.org/2/library/threading.html)
*   eventlet：支持 WSGI 的异步框架。[官网](http://eventlet.net/)
*   gevent：一个基于协程的 Python 网络库，使用 [greenlet](https://github.com/python-greenlet/greenlet)。[官网](http://www.gevent.org/)
*   Tomorrow：用于产生异步代码的神奇的装饰器语法实现。[官网](https://github.com/madisonmay/Tomorrow)
*   uvloop：在 libuv 之上超快速实现 asyncio 事件循环。[官网](https://github.com/MagicStack/uvloop)

### 网络

用于网络编程的库。

*   asyncio：(Python 标准库) 异步 I/O, 事件循环, 协程以及任务。[官网](https://docs.python.org/3/library/asyncio.html)
*   [Twisted](http://hao.importnew.com/twisted/)：一个事件驱动的网络引擎。[官网](https://twistedmatrix.com/trac/)
*   pulsar：事件驱动的并发框架。[官网](https://github.com/quantmind/pulsar)
*   diesel：基于 Greenlet 的事件 I/O 框架。[官网](https://github.com/dieseldev/diesel)
*   pyzmq：一个 ZeroMQ 消息库的 Python 封装。[官网](http://zeromq.github.io/pyzmq/)
*   Toapi：一个轻巧，简单，快速的 Flask 库，致力于为所有网站提供 API 服务。[官网](https://github.com/gaojiuli/toapi)
*   txZMQ：基于 Twisted 的 ZeroMQ 消息库的 Python 封装。[官网](https://github.com/smira/txZMQ)





### 密码学

*   cryptography：这个软件包意在提供密码学基本内容和方法提供给 Python 开发者。[官网](https://cryptography.io/en/latest/)
*   hashids：在 Python 中实现 [hashids](http://hashids.org/) 。[官网](https://github.com/davidaurelio/hashids-python)
*   Paramiko：SSHv2 协议的 Python (2.6+, 3.3+) ，提供客户端和服务端的功能。[官网](http://www.paramiko.org/)
*   Passlib：安全密码存储／哈希库，[官网](https://pythonhosted.org/passlib/)
*   PyCrypto：Python 密码学工具箱。[官网](https://www.dlitz.net/software/pycrypto/)
*   PyNacl：网络和密码学(NaCl) 库的 Python 绑定。[官网](https://github.com/pyca/pynacl)



### 日志

用来生成和操作日志的库。

*   logging：(Python 标准库) 为 Python 提供日志功能。[官网](https://docs.python.org/2/library/logging.html)
*   logbook：Logging 库的替代品。[官网](http://pythonhosted.org/Logbook/)
*   Eliot：为复杂的和分布式系统创建日志。[官网](https://eliot.readthedocs.org/en/latest/)
*   Raven：Sentry 的 Python 客户端。[官网](http://raven.readthedocs.org/en/latest/)
*   Sentry：实时记录和收集日志的服务器。[官网](https://pypi.python.org/pypi/sentry)



### 科学计算和数据分析

用来进行科学计算和数据分析的库。

*   astropy：一个天文学 Python 库。[官网](http://www.astropy.org/)
*   [bcbio-nextgen](http://hao.importnew.com/bcbio-nextgen/)：这个工具箱为全自动高通量测序分析提供符合最佳实践的处理流程。[官网](https://github.com/chapmanb/bcbio-nextgen)
*   bccb：生物分析相关代码集合。[官网](https://github.com/chapmanb/bcbb)
*   Biopython：Biopython 是一组可以免费使用的用来进行生物计算的工具。[官网](http://biopython.org/wiki/MainPage)
*   [blaze](http://hao.importnew.com/blaze/)：NumPy 和 Pandas 的大数据接口。[官网](http://blaze.readthedocs.org/en/latest/index.html)
*   [cclib](http://hao.importnew.com/cclib/)：一个用来解析和解释计算化学软件包输出结果的库。[官网](http://cclib.github.io/)
*   NetworkX：一个为复杂网络设计的高性能软件。[官网](https://networkx.github.io/)
*   Neupy：执行和测试各种不同的人工神经网络算法。[官网](http://neupy.com/pages/home.html)
*   Numba：Python JIT (just in time) 编译器，针对科学用的 Python ，由 Cython 和 NumPy 的开发者开发。[官网](http://numba.pydata.org/)
*   [NumPy](http://hao.importnew.com/numpy/)：使用 Python 进行科学计算的基础包。[官网](http://www.numpy.org/)
*   Open Babel：一个化学工具箱，用来描述多种化学数据。[官网](http://openbabel.org/wiki/MainPage)
*   [Open Mining](http://hao.importnew.com/open-mining/)：使用 Python 挖掘商业情报 (BI) (Pandas web 接口)。[官网](https://github.com/mining/mining)
*   [orange](http://hao.importnew.com/orange/)：通过可视化编程或 Python 脚本进行数据挖掘，数据可视化，分析和机器学习。[官网](http://orange.biolab.si/)
*   Pandas：提供高性能，易用的数据结构和数据分析工具。[官网](http://pandas.pydata.org/)
*   PyDy：PyDy 是 Python Dynamics 的缩写，用来为动力学运动建模工作流程提供帮助， 基于 NumPy, SciPy, IPython 和 matplotlib。[官网](http://www.pydy.org/)
*   [PyMC](http://hao.importnew.com/pymc/)：马尔科夫链蒙特卡洛采样工具。[官网](https://github.com/pymc-devs/pymc3)
*   RDKit：化学信息学和机器学习软件。[官网](http://www.rdkit.org/)
*   [SciPy](http://hao.importnew.com/scipy/)：由一些基于 Python ，用于数学，科学和工程的开源软件构成的生态系统。[官网](http://www.scipy.org/)
*   [statsmodels](http://hao.importnew.com/statsmodels/)：统计建模和计量经济学。[官网](https://github.com/statsmodels/statsmodels)
*   SymPy：一个用于符号数学的 Python 库。[官网](https://github.com/sympy/sympy)
*   zipline：一个 Python 算法交易库。[官网](https://github.com/quantopian/zipline)
*   [Bayesian-belief-networks](http://hao.importnew.com/bayesian-belief-networks/)：优雅的贝叶斯信念网络框架。[官网](https://github.com/eBay/bayesian-belief-networks)

### 数据可视化

进行数据可视化的库。 参见: [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization)。

*   matplotlib：一个 Python 2D 绘图库。[官网](http://matplotlib.org/)
*   bokeh：用 Python 进行交互式 web 绘图。[官网](https://github.com/bokeh/bokeh)
*   ggplot：ggplot2 给 R 提供的 API 的 Python 版本。[官网](https://github.com/yhat/ggplot)
*   plotly：协同 Python 和 matplotlib 工作的 web 绘图库。[官网](https://plot.ly/python/)
*   pyecharts：基于百度 Echarts 的数据可视化库。[官网](https://github.com/chenjiandongx/pyecharts)
*   pygal：一个 Python SVG 图表创建工具。[官网](http://www.pygal.org/en/latest/)
*   pygraphviz：Graphviz 的 Python 接口。[官网](https://pypi.python.org/pypi/pygraphviz)
*   PyQtGraph：交互式实时 2D/3D/ 图像绘制及科学/工程学组件。[官网](http://www.pyqtgraph.org/)
*   SnakeViz：一个基于浏览器的 Python's cProfile 模块输出结果查看工具。[官网](http://jiffyclub.github.io/snakeviz/)
*   vincent：把 Python 转换为 Vega 语法的转换工具。[官网](https://github.com/wrobstory/vincent)
*   VisPy：基于 OpenGL 的高性能科学可视化工具。[官网](http://vispy.org/)

### 计算机视觉

计算机视觉库。

*   OpenCV：开源计算机视觉库。[官网](http://opencv.org/)
*   pyocr：Tesseract 和 Cuneiform 的包装库。[官网](https://github.com/jflesch/pyocr)
*   pytesseract：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的另一包装库。[官网](https://github.com/madmaze/pytesseract)
*   [SimpleCV](http://hao.importnew.com/simplecv/)：一个用来创建计算机视觉应用的开源框架。[官网](http://simplecv.org/)

### 机器学习

机器学习库。 参见: [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).

*   Caffe: 一个 [Caffe](https://github.com/BVLC/caffe) 的 python 接口。[官网](http://caffe.berkeleyvision.org)
*   [Caffe2](https://github.com/caffe2/caffe2/)：一个轻量级的，模块化的，可扩展的深度学习框架。[官网](https://caffe2.ai/)
*   Crab：灵活、快速的推荐引擎。[官网](https://github.com/muricoca/crab)
*   gensim：人性化的话题建模库。[官网](https://github.com/piskvorky/gensim)
*   hebel：GPU 加速的深度学习库。[官网](https://github.com/hannes-brt/hebel)
*   [keras](https://github.com/keras-team/keras): 以 tensorflow/theano/CNTK 为后端的深度学习封装库，快速上手神经网络。[官网](https://keras.io/)
*   [MXNet](https://github.com/apache/incubator-mxnet)：一个高效和灵活的深度学习框架。[官网](http://mxnet.incubator.apache.org/)
*   NuPIC：智能计算 Numenta 平台。[官网](https://github.com/numenta/nupic)
*   pattern：Python 网络挖掘模块。[官网](https://github.com/clips/pattern)
*   [PyBrain](http://hao.importnew.com/pybrain/)：另一个 Python 机器学习库。[官网](https://github.com/pybrain/pybrain)
*   pydeep：Python 深度学习库。[官网](https://github.com/andersbll/deeppy)
*   [Pylearn2](http://hao.importnew.com/pylearn2/)：一个基于 [Theano](https://github.com/Theano/Theano) 的机器学习库。[官网](https://github.com/lisa-lab/pylearn2)
*   [python-recsys](http://hao.importnew.com/python-recsys/)：一个用来实现推荐系统的 Python 库。[官网](https://github.com/ocelma/python-recsys)
*   [Pytorch](https://github.com/pytorch/pytorch)：一个具有张量和动态神经网络，并有强大 GPU 加速能力的深度学习框架。[官网](http://pytorch.org/)
*   scikit-learn：基于 SciPy 构建的机器学习 Python 模块。[官网](http://scikit-learn.org/)
*   skflow：一个 [TensorFlow](https://github.com/tensorflow/tensorflow) 的简化接口(模仿 scikit-learn)。[官网](https://github.com/tensorflow/skflow)
*   [TensorFlow](https://github.com/tensorflow/tensorflow)：谷歌开源的最受欢迎的深度学习框架。[官网](http://tensorflow.org/)
*   Theano：一个快速数值计算库。[官网](https://github.com/Theano/Theano)
*   vowpalporpoise：轻量级 [Vowpal Wabbit](https://github.com/JohnLangford/vowpalwabbit/) 的 Python 封装。[官网](https://github.com/josephreisinger/vowpalporpoise)

### MapReduce

MapReduce 框架和库。

*   [dpark](http://hao.importnew.com/dpark/)：Spark 的 Python 克隆版，一个类似 MapReduce 的框架。[官网](https://github.com/douban/dpark)
*   dumbo：这个 Python 模块可以让人轻松的编写和运行 Hadoop 程序。[官网](https://github.com/klbostee/dumbo)
*   luigi：这个模块帮你构建批处理作业的复杂流水线。[官网](https://github.com/spotify/luigi)
*   mrjob：在 Hadoop 或 Amazon Web Services 上运行 MapReduce 任务。[官网](https://github.com/Yelp/mrjob)
*   PySpark：Spark 的 Python API 。[官网](http://spark.apache.org/docs/latest/programming-guide.html)
*   streamparse：运行针对事实数据流的 Python 代码。集成了 [Apache Storm](http://storm.apache.org/)。[官网](https://github.com/Parsely/streamparse)

### 函数式编程

使用 Python 进行函数式编程。

*   CyToolz：Toolz 的 Cython 实现 : 高性能函数式工具。[官网](https://github.com/pytoolz/cytoolz/)
*   fn.py：在 Python 中进行函数式编程 : 实现了一些享受函数式编程缺失的功能。[官网](https://github.com/kachayev/fn.py)
*   funcy：炫酷又实用的函数式工具。[官网](https://github.com/Suor/funcy)
*   Toolz：一组用于迭代器，函数和字典的函数式编程工具。[官网](https://github.com/pytoolz/toolz)

### 第三方 API

用来访问第三方 API 的库。 参见： [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers)。

*   apache-libcloud：一个为各种云设计的 Python 库。[官网](https://libcloud.apache.org/)
*   boto：Amazon Web Services 的 Python 接口。[官网](https://github.com/boto/boto)
*   django-wordpress：WordPress models and views for Django.[官网](https://github.com/sunlightlabs/django-wordpress/)
*   facebook-sdk：Facebook 平台的 Python SDK.[官网](https://github.com/mobolic/facebook-sdk)
*   facepy：Facepy 让和 Facebook's Graph API 的交互变得更容易。[官网](https://github.com/jgorset/facepy)
*   gmail：Gmail 的 Python 接口。[官网](https://github.com/charlierguo/gmail)
*   google-api-python-client：Python 用的 Google APIs 客户端库。[官网](https://github.com/google/google-api-python-client)
*   gspread：Google 电子表格的 Python API.[官网](https://github.com/burnash/gspread)
*   twython：Twitter API 的封装。[官网](https://github.com/ryanmcgrath/twython)

### DevOps 工具

用于 DevOps 的软件和库。

*   Ansible：一个非常简单的 IT 自动化平台。[官网](https://github.com/ansible/ansible)
*   SaltStack：基础设施自动化和管理系统。[官网](https://github.com/saltstack/salt)
*   OpenStack：用于构建私有和公有云的开源软件。[官网](http://www.openstack.org/)
*   Docker Compose：快速，分离的开发环境，使用 Docker。[官网](https://docs.docker.com/compose/)
*   Fabric：一个简单的，Python 风格的工具，用来进行远程执行和部署。[官网](http://www.fabfile.org/)
*   cuisine：为 Fabric 提供一系列高级函数。[官网](https://github.com/sebastien/cuisine)
*   Fabtools：一个用来编写超赞的 Fabric 文件的工具。[官网](https://github.com/ronnix/fabtools)
*   gitapi：Git 的纯 Python API。[官网](https://bitbucket.org/haard/gitapi)
*   hgapi：Mercurial 的纯 Python API。[官网](https://bitbucket.org/haard/hgapi)
*   honcho：[Foreman](https://github.com/ddollar/foreman) 的 Python 克隆版，用来管理基于 [Procfile](https://devcenter.heroku.com/articles/procfile) 的应用。[官网](https://github.com/nickstenning/honcho)
*   pexpect：Controlling interactive programs in a pseudo-terminal like 在一个伪终端中控制交互程序，就像 GNU expect 一样。[官网](https://github.com/pexpect/pexpect)
*   psutil：一个跨平台进程和系统工具模块。[官网](https://github.com/giampaolo/psutil)
*   supervisor：UNIX 的进程控制系统。[官网](https://github.com/Supervisor/supervisor)

### 任务调度

任务调度库。

*   APScheduler：轻巧但强大的进程内任务调度，使你可以调度函数。[官网](http://apscheduler.readthedocs.org/en/latest/)
*   django-schedule：一个 Django 排程应用。[官网](https://github.com/thauber/django-schedule)
*   doit：一个任务执行和构建工具。[官网](http://pydoit.org/)
*   gunnery：分布式系统使用的多用途任务执行工具 ，具有 web 交互界面。[官网](https://github.com/gunnery/gunnery)
*   Joblib：一组为 Python 提供轻量级作业流水线的工具。[官网](http://pythonhosted.org/joblib/index.html)
*   Plan：如有神助地编写 crontab 文件。[官网](https://github.com/fengsp/plan)
*   schedule：人性化的 Python 任务调度库。[官网](https://github.com/dbader/schedule)
*   Spiff：使用纯 Python 实现的强大的工作流引擎。[官网](https://github.com/knipknap/SpiffWorkflow)
*   TaskFlow：一个可以让你方便执行任务的 Python 库，一致并且可靠。[官网](http://docs.openstack.org/developer/taskflow/)
*   AirFlow：Airflow 是Airbnb公司开源的，是一个工作流分配管理系统，通过有向非循环图的方式管理任务流程，设置任务依赖关系和时间调度。[官方](https://airflow.incubator.apache.org/)

### 外来函数接口

使用外来函数接口的库。

*   cffi：用来调用 C 代码的外来函数接口。[官网](https://pypi.python.org/pypi/cffi)
*   [ctypes](http://hao.importnew.com/ctypes/)：(Python 标准库) 用来调用 C 代码的外来函数接口。[官网](https://docs.python.org/2/library/ctypes.html)
*   PyCUDA：Nvidia CUDA API 的封装。[官网](https://mathema.tician.de/software/pycuda/)
*   SWIG：简化的封装和接口生成器。[官网](http://www.swig.org/Doc1.3/Python.html)

### 高性能

让 Python 更快的库。

*   Cython：优化的 Python 静态编译器。使用类型混合使 Python 编译成 C 或 C++ 模块来获得性能的极大提升。[官网](http://cython.org/)
*   PeachPy：嵌入 Python 的 x86-64 汇编器。可以被用作 Python 内联的汇编器或者是独立的汇编器，用于 Windows, Linux, OS X, Native Client 或者 Go 。[官网](https://github.com/Maratyszcza/PeachPy)
*   PyPy：使用 Python 实现的 Python。解释器使用黑魔法加快 Python 运行速度且不需要加入额外的类型信息。[官网](http://pypy.org/)
*   [Pyston](http://hao.importnew.com/pyston-llvm-jit/)：使用 LLVM 和现代 JIT 技术构建的 Python 实现，目标是为了获得很好的性能。[官网](https://github.com/dropbox/pyston)
*   Stackless Python：一个强化版的 Python。[官网](https://bitbucket.org/stackless-dev/stackless/overview)

### 微软的 Windows 平台

在 Windows 平台上进行 Python 编程。

*   Python(x,y)：面向科学应用的 Python 发行版，基于 Qt 和 Spyder。[官网](http://python-xy.github.io/)
*   pythonlibs：非官方的 Windows 平台 Python 扩展二进制包。[官网](http://www.lfd.uci.edu/~gohlke/pythonlibs/)
*   PythonNet：Python 与 .NET 公共语言运行库 (CLR)的集成。[官网](https://github.com/pythonnet/pythonnet)
*   PyWin32：针对 Windows 的 Python 扩展。[官网](https://sourceforge.net/projects/pywin32/)
*   WinPython：Windows 7/8 系统下便携式开发环境。[官网](https://winpython.github.io/)

### 网络可视化和 SDN

用来进行网络可视化和 SDN(软件定义网络)的工具和库。

*   Mininet：一款流行的网络模拟器以及用 Python 编写的 API。[官网](http://mininet.org/)
*   POX：一个针对基于 Python 的软件定义网络应用（例如 OpenFlow SDN 控制器）的开源开发平台。[官网](https://github.com/noxrepo/pox)
*   Pyretic：火热的 SDN 编程语言中的一员，为网络交换机和模拟器提供强大的抽象能力。[官网](http://frenetic-lang.org/pyretic/)
*   SDX Platform：基于 SDN 的 IXP 实现，影响了 Mininet, POX 和 Pyretic。[官网](https://github.com/sdn-ixp/internet2award)
*   NRU：一个基于组件的软件定义网络框架。[官网](http://ryu.readthedocs.io/en/latest/)

### 硬件

用来对硬件进行编程的库。

*   ino：操作 [Arduino](https://www.arduino.cc/) 的命令行工具。[官网](http://inotool.org/) 
*   Pyro：Python 机器人编程库。[官网](http://pyrorobotics.com/)
*   PyUserInput：跨平台的，控制鼠标和键盘的模块。[官网](https://github.com/SavinaRoja/PyUserInput)
*   scapy：一个非常棒的操作数据包的库。[官网](https://github.com/secdev/scapy)
*   wifi：一个 Python 库和命令行工具用来在 Linux 平台上操作 WiFi。[官网](https://wifi.readthedocs.org/en/latest/)
*   Pingo：Pingo 为类似 Raspberry Pi，pcDuino， Intel Galileo 等设备提供统一的 API 用以编程。[官网](http://www.pingo.io/)

### 兼容性

帮助从 Python 2 向 Python 3 迁移的库。

*   Python-Future：这就是 Python 2 和 Python 3 之间丢失的那个兼容性层。[官网](http://python-future.org/index.html)
*   Python-Modernize：使 Python 代码更加现代化以便最终迁移到 Python 3。[官网](https://github.com/mitsuhiko/python-modernize)
*   Six：Python 2 和 3 的兼容性工具。[官网](https://pypi.python.org/pypi/six)


## Python

#### 计算机视觉

*   [SimpleCV](http://hao.importnew.com/simplecv/)：开源计算机视觉框架，可以访问如OpenCV等高性能计算机视觉库使用Python编写，可以在Mac、Windows以及Ubuntu上运行。[官网](http://simplecv.org/)。





## 通用机器学习

*   Bayesian Methods for Hackers：Python语言概率规划的电子书。[官网](https://github.com/CamDavidsonPilon/。Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)
*   MLlib in Apache Spark：Spark下的分布式机器学习库。[官网](http://spark.apache.org/docs/latest/mllib-guide.html)
*   scikit-learn：基于SciPy的机器学习模块。[官网](http://scikit-learn.org/)
*   graphlab-create：包含多种机器学习模块的库（回归、聚类、推荐系统、图分析等），基于可以磁盘存储的DataFrame。[官网](http://graphlab.com/products/create/docs/)
*   BigML：连接外部服务器的库。[官网](https://bigml.com/)
*   pattern：Python的web挖掘模块。[官网](https://github.com/clips/pattern)
*   NuPIC：Numenta公司的智能计算平台。[官网](https://github.com/numenta/nupic)
*   Pylearn2：基于Theano的机器学习库。[官网](https://github.com/lisa-lab/pylearn2)
*   hebel：Python编写的使用GPU加速的深度学习库。[官网](https://github.com/hannes-brt/hebel)
*   gensim：主题建模工具。[官网](https://github.com/piskvorky/gensim)
*   PyBrain：另一个机器学习库。[官网](https://github.com/pybrain/pybrain)
*   Crab：可扩展的、快速推荐引擎。[官网](https://github.com/muricoca/crab)
*   python-recsys：Python实现的推荐系统。[官网](https://github.com/ocelma/python-recsys)
*   thinking bayes：关于贝叶斯分析的书籍。[官网](https://github.com/AllenDowney/ThinkBayes)
*   Restricted Boltzmann Machines：Python实现的受限波尔兹曼机。[官网](https://github.com/echen/restricted-boltzmann-machines)
*   Bolt：在线学习工具箱。[官网](https://github.com/pprett/bolt)
*   CoverTree：cover tree的Python实现，scipy.spatial.kdtree便捷的替代。[官网](https://github.com/patvarilly/CoverTree)
*   nilearn：Python实现的神经影像学机器学习库。[官网](https://github.com/nilearn/nilearn)
*   Shogun：机器学习工具箱。[官网](https://github.com/shogun-toolbox/shogun)
*   Pyevolve：遗传算法框架。[官网](https://github.com/perone/Pyevolve)
*   Caffe：考虑了代码清洁、可读性及速度的深度学习框架。[官网](http://caffe.berkeleyvision.org/)
*   breze：深度及递归神经网络的程序库，基于Theano。[官网](https://github.com/breze-no-salt/breze)



##  数据分析/数据可视化

* SciPy：基于Python的数学、科学、工程开源软件生态系统。[官网](http://www.scipy.org/)
* NumPy：Python科学计算基础包。[官网](http://www.numpy.org/)
* Numba：Python的低级虚拟机JIT编译器，Cython and NumPy的开发者编写，供科学计算使用。[官网](http://numba.pydata.org/)
* NetworkX：为复杂网络使用的高效软件。[官网](https://networkx.github.io/)
* Pandas：这个库提供了高性能、易用的数据结构及数据分析工具。[官网](http://pandas.pydata.org/)
* [Open Mining](http://hao.importnew.com/open-mining/)：Python中的商业智能工具（Pandas web接口）。[官网](https://github.com/avelino/mining)
* [PyMC](http://hao.importnew.com/pymc/)：MCMC采样工具包。[官网](https://github.com/pymc-devs/pymc)
* zipline：Python的算法交易库。[官网](https://github.com/quantopian/zipline)
* PyDy：全名Python Dynamics，协助基于NumPy、SciPy、IPython以及 matplotlib的动态建模工作流。[官网](https://pydy.org/)
* SymPy：符号数学Python库。[官网](https://github.com/sympy/sympy)
* statsmodels：Python的统计建模及计量经济学库。[官网](https://github.com/statsmodels/statsmodels)
* astropy：Python天文学程序库，社区协作编写。[官网](http://www.astropy.org/)
* matplotlib：Python的2D绘图库。[官网](http://matplotlib.org/)
* bokeh：Python的交互式Web绘图库。[官网](https://github.com/ContinuumIO/bokeh)
* plotly：Python and matplotlib的协作web绘图库。[官网](https://plot.ly/python)
* vincent：将Python数据结构转换为Vega可视化语法。[官网](https://github.com/wrobstory/vincent)
* d3py：Python的绘图库，基于D3.js。[官网](https://github.com/mikedewar/d3py)
* ggplot：和R语言里的ggplot2提供同样的API。[官网](https://github.com/yhat/ggplot)
* Kartograph.py：Python中渲染SVG图的库，效果漂亮。[官网](https://github.com/kartograph/kartograph.py)
* pygal：Python下的SVG图表生成器。[官网](http://pygal.org/)
* pycascading：[官网](https://github.com/twitter/pycascading)
* 近20年各省的GDP、人口数、教育经费、消费水平、财政支出和收入数据。  [官网](https://github.com/thunderhit/bar_chart_race_cn/blob/master/README.md)
* Airbnb New User Bookings（Airbnb新用户的民宿预定结果预测）。[kaggle官网](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/notebooks)       [CSDN博客](https://blog.csdn.net/datawhale/article/details/80847662)
* 

#### 杂项脚本/iPython笔记/代码库[](https://github.com/josephmisiti/awesome-machine-learning/blob/master/README.md#misc-scripts--ipython-notebooks--codebases)

*   pattern_classification：[官网](https://github.com/rasbt/pattern_classification)
*   thinking stats 2：[官网](https://github.com/Wavelets/ThinkStats2)
*   hyperopt：[官网](https://github.com/hyperopt/hyperopt-sklearn)
*   numpic：[官网](https://github.com/numenta/nupic)
*   2012-paper-diginorm：[官网](https://github.com/ged-lab/2012-paper-diginorm)
*   ipython-notebooks：[官网](https://github.com/ogrisel/notebooks)
*   decision-weights：[官网](https://github.com/CamDavidsonPilon/decision-weights)
*   Sarah Palin LDA：Sarah Palin关于主题建模的电邮。[官网](https://github.com/Wavelets/sarah-palin-lda)
*   Diffusion Segmentation：基于扩散方法的图像分割算法集合。[官网](https://github.com/Wavelets/diffusion-segmentation)
*   Scipy Tutorials：SciPy教程，已过时，请查看scipy-lecture-notes。[官网](https://github.com/Wavelets/scipy-tutorials)
*   Crab：Python的推荐引擎库。[官网](https://github.com/marcelcaraciolo/crab)
*   BayesPy：Python中的贝叶斯推断工具。[官网](https://github.com/maxsklar/BayesPy)
*   scikit-learn tutorials：scikit-learn学习笔记系列。[官网](https://github.com/GaelVaroquaux/scikit-learn-tutorial)
*   sentiment-analyzer：推特情绪分析器。[官网](https://github.com/madhusudancs/sentiment-analyzer)
*   group-lasso：坐标下降算法实验，应用于（稀疏）群套索模型。[官网](https://github.com/fabianp/group_lasso)
*   mne-python-notebooks：使用 mne-python进行EEG/MEG数据处理的IPython笔记。[官网](https://github.com/mne-tools/mne-python-notebooks)
*   pandas cookbook：使用Python pandas库的方法书。[官网](https://github.com/jvns/pandas-cookbook)
*   climin：机器学习的优化程序库，用Python实现了梯度下降、LBFGS、rmsprop、adadelta 等算法。[官网](https://github.com/BRML/climin)

#### [](https://github.com/josephmisiti/awesome-machine-learning/blob/master/README.md#kaggle-competition-source-code)Kaggle竞赛源代码

*   wiki challange：Kaggle上一个维基预测挑战赛 Dell Zhang解法的实现。[官网](https://github.com/hammer/wikichallenge)
*   kaggle insults：Kaggle上”从社交媒体评论中检测辱骂“竞赛提交的代码。[官网](https://github.com/amueller/kaggle_insults)
*   kaggle_acquire-valued-shoppers-challenge：Kaggle预测回头客挑战赛的代码。[官网](https://github.com/MLWave/。kaggle_acquire-valued-shoppers-challenge)
*   kaggle-cifar：Kaggle上CIFAR-10 竞赛的代码，使用cuda-convnet。[官网](https://github.com/zygmuntz/kaggle-cifar)
*   kaggle-blackbox：Kaggle上blackbox赛代码，关于深度学习。[官网](https://github.com/zygmuntz/kaggle-blackbox)
*   kaggle-accelerometer：Kaggle上加速度计数据识别用户竞赛的代码。[官网](https://github.com/zygmuntz/kaggle-accelerometer)
*   kaggle-advertised-salaries：Kaggle上用广告预测工资竞赛的代码。[官网](https://github.com/zygmuntz/kaggle-advertised-salaries) 
*   kaggle amazon：Kaggle上给定员工角色预测其访问需求竞赛的代码。[官网](https://github.com/zygmuntz/kaggle-amazon)
*   kaggle-bestbuy_big：Kaggle上根据bestbuy用户查询预测点击商品竞赛的代码（大数据版）。[官网](https://github.com/zygmuntz/kaggle-bestbuy_big)
*   kaggle-bestbuy_small：Kaggle上根据bestbuy用户查询预测点击商品竞赛的代码（小数据版）。[官网](https://github.com/zygmuntz/kaggle-bestbuy_small)
*   Kaggle Dogs vs. Cats：Kaggle上从图片中识别猫和狗竞赛的代码。[官网](https://github.com/kastnerkyle/kaggle-dogs-vs-cats)
*   Kaggle Galaxy Challenge：Kaggle上遥远星系形态分类竞赛的优胜代码。[官网](https://github.com/benanne/kaggle-galaxies)
*   Kaggle Gender：Kaggle竞赛，从笔迹区分性别。[官网](https://github.com/zygmuntz/kaggle-gender)
*   Kaggle Merck：Kaggle上预测药物分子活性竞赛的代码（默克制药赞助）。[官网](https://github.com/zygmuntz/kaggle-merck)
*   Kaggle Stackoverflow：Kaggle上 预测StackOverflow网站问题是否会被关闭竞赛的代码。[官网](https://github.com/zygmuntz/kaggle-stackoverflow)
*   wine-quality：预测红酒质量。[官网](https://github.com/zygmuntz/wine-quality)
*   数据科学竞赛各种baseline代码、思路分享。[官网](https://github.com/datawhalechina/competition-baseline)
*   python编程相关技巧。[官网](https://www.cjavapy.com/category/23/)
*   













