### Accidentally solved an R issue
> install.packages("swirl")
将程序包安装入‘C:/Users/nasca/Documents/R/win-library/3.4’
(因为‘lib’没有被指定)
--- 在此連線階段时请选用CRAN的鏡子 ---
Warning: failed to download mirrors file (无法打开URL'https://cran.r-project.org/CRAN_mirrors.csv'); using local file 'C:/PROGRA~1/R/R-34~1.0/doc/CRAN_mirrors.csv'
Warning: 无法在貯藏處https://cran.stat.auckland.ac.nz/src/contrib中读写索引:
  无法打开URL'https://cran.stat.auckland.ac.nz/src/contrib/PACKAGES'
Warning: 无法在貯藏處http://www.stats.ox.ac.uk/pub/RWin/src/contrib中读写索引:
  无法打开URL'http://www.stats.ox.ac.uk/pub/RWin/src/contrib/PACKAGES'
Warning: 无法在貯藏處https://cran.stat.auckland.ac.nz/bin/windows/contrib/3.4中读写索引:
  无法打开URL'https://cran.stat.auckland.ac.nz/bin/windows/contrib/3.4/PACKAGES'
Warning: 无法在貯藏處http://www.stats.ox.ac.uk/pub/RWin/bin/windows/contrib/3.4中读写索引:
  无法打开URL'http://www.stats.ox.ac.uk/pub/RWin/bin/windows/contrib/3.4/PACKAGES'
Warning messages:
1: In download.file(url, destfile = f, quiet = TRUE) :
  InternetOpenUrl失败:’'
2: package ‘swirl’ is not available (for R version 3.4.0) 
> chooseCRANmirror()
Warning: failed to download mirrors file (无法打开URL'https://cran.r-project.org/CRAN_mirrors.csv'); using local file 'C:/PROGRA~1/R/R-34~1.0/doc/CRAN_mirrors.csv'
Warning message:
In download.file(url, destfile = f, quiet = TRUE) : InternetOpenUrl失败:’'
> install.packages('package_name', dependencies=TRUE, repos='http://cran.rstudio.com/')
将程序包安装入‘C:/Users/nasca/Documents/R/win-library/3.4’
(因为‘lib’没有被指定)
Warning: 无法在貯藏處http://cran.rstudio.com/src/contrib中读写索引:
  无法打开URL'http://cran.rstudio.com/src/contrib/PACKAGES'
Warning: 无法在貯藏處http://cran.rstudio.com/bin/windows/contrib/3.4中读写索引:
  无法打开URL'http://cran.rstudio.com/bin/windows/contrib/3.4/PACKAGES'
Warning message:
package ‘package_name’ is not available (for R version 3.4.0) 
> chooseCRANmirror()
Warning: failed to download mirrors file (无法打开URL'https://cran.r-project.org/CRAN_mirrors.csv'); using local file 'C:/PROGRA~1/R/R-34~1.0/doc/CRAN_mirrors.csv'
Warning message:
In download.file(url, destfile = f, quiet = TRUE) : InternetOpenUrl失败:’'
> library(RCurl); url.exists("google.com")
Error in library(RCurl) : 不存在叫‘RCurl’这个名字的程辑包
> options(repos = c(CRAN = "http://cloud.r-project.org")); available.packages()
Warning: 无法在貯藏處http://cloud.r-project.org/src/contrib中读写索引:
  无法打开URL'http://cloud.r-project.org/src/contrib/PACKAGES'
     Package Version Priority Depends Imports LinkingTo Suggests Enhances
     License License_is_FOSS License_restricts_use OS_type Archs MD5sum
     NeedsCompilation File Repository
> install.packages("lgcp")
将程序包安装入‘C:/Users/nasca/Documents/R/win-library/3.4’
(因为‘lib’没有被指定)
Warning: 无法在貯藏處http://cloud.r-project.org/src/contrib中读写索引:
  无法打开URL'http://cloud.r-project.org/src/contrib/PACKAGES'
Warning: 无法在貯藏處http://cloud.r-project.org/bin/windows/contrib/3.4中读写索引:
  无法打开URL'http://cloud.r-project.org/bin/windows/contrib/3.4/PACKAGES'
Warning message:
package ‘lgcp’ is not available (for R version 3.4.0) 
> > install.packages("devtools")
错误: 意外的'>' in ">"
> > library(devtools)
错误: 意外的'>' in ">"
> > install_github("swirldev/swirl", ref = "dev")
错误: 意外的'>' in ">"
> > library(swirl)
错误: 意外的'>' in ">"
> > swirl()
错误: 意外的'>' in ">"
> install.packages("devtools")
将程序包安装入‘C:/Users/nasca/Documents/R/win-library/3.4’
(因为‘lib’没有被指定)
Warning: 无法在貯藏處http://cloud.r-project.org/src/contrib中读写索引:
  无法打开URL'http://cloud.r-project.org/src/contrib/PACKAGES'
Warning: 无法在貯藏處http://cloud.r-project.org/bin/windows/contrib/3.4中读写索引:
  无法打开URL'http://cloud.r-project.org/bin/windows/contrib/3.4/PACKAGES'
Warning message:
package ‘devtools’ is not available (for R version 3.4.0) 
> library(devtools)
Error in library(devtools) : 不存在叫‘devtools’这个名字的程辑包
> install_github("swirldev/swirl", ref = "dev")
Error in install_github("swirldev/swirl", ref = "dev") : 
  没有"install_github"这个函数
> library(swirl)
Error in library(swirl) : 不存在叫‘swirl’这个名字的程辑包
> swirl()
Error in swirl() : 没有"swirl"这个函数
> install.packages("swirl")
将程序包安装入‘C:/Users/nasca/Documents/R/win-library/3.4’
(因为‘lib’没有被指定)
Warning: 无法在貯藏處http://cloud.r-project.org/src/contrib中读写索引:
  无法打开URL'http://cloud.r-project.org/src/contrib/PACKAGES'
Warning: 无法在貯藏處http://cloud.r-project.org/bin/windows/contrib/3.4中读写索引:
  无法打开URL'http://cloud.r-project.org/bin/windows/contrib/3.4/PACKAGES'
Warning message:
package ‘swirl’ is not available (for R version 3.4.0) 
> chooseCRANmirror()
Warning: failed to download mirrors file (无法打开URL'https://cran.r-project.org/CRAN_mirrors.csv'); using local file 'C:/PROGRA~1/R/R-34~1.0/doc/CRAN_mirrors.csv'
Warning message:
In download.file(url, destfile = f, quiet = TRUE) : InternetOpenUrl失败:’'
> options(download.file.method = "internal") 
> chooseCRANmirror()
Warning: failed to download mirrors file (scheme not supported in URL 'https://cran.r-project.org/CRAN_mirrors.csv'); using local file 'C:/PROGRA~1/R/R-34~1.0/doc/CRAN_mirrors.csv'
> install.packages("swirl")
将程序包安装入‘C:/Users/nasca/Documents/R/win-library/3.4’
(因为‘lib’没有被指定)
Warning: 无法在貯藏處https://cran.wu.ac.at/src/contrib中读写索引:
  scheme not supported in URL 'https://cran.wu.ac.at/src/contrib/PACKAGES'
Warning: 无法在貯藏處https://cran.wu.ac.at/bin/windows/contrib/3.4中读写索引:
  scheme not supported in URL 'https://cran.wu.ac.at/bin/windows/contrib/3.4/PACKAGES'
Warning message:
package ‘swirl’ is not available (for R version 3.4.0) 
> Sys.setenv(http_proxy="<a href="http://proxyserver:port">http://proxyserver:port") 
错误: unexpected symbol in "Sys.setenv(http_proxy="<a href="http"
> options(repos="http://cloud.r-project.org/") 
> options(download.file.method="internal") 
> install.packages("swirl",dependencies = T)
将程序包安装入‘C:/Users/nasca/Documents/R/win-library/3.4’
(因为‘lib’没有被指定)
还安装相依关系‘magrittr’, ‘crayon’, ‘praise’, ‘R6’, ‘jsonlite’, ‘mime’, ‘curl’, ‘openssl’, ‘bitops’, ‘stringr’, ‘testthat’, ‘httr’, ‘yaml’, ‘RCurl’, ‘digest’, ‘stringi’

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/magrittr_1.5.zip'
Content type 'application/zip' length 155626 bytes (151 KB)
downloaded 151 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/crayon_1.3.2.zip'
Content type 'application/zip' length 705720 bytes (689 KB)
downloaded 689 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/praise_1.0.0.zip'
Content type 'application/zip' length 17918 bytes (17 KB)
downloaded 17 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/R6_2.2.1.zip'
Content type 'application/zip' length 319404 bytes (311 KB)
downloaded 311 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/jsonlite_1.4.zip'
Content type 'application/zip' length 1124546 bytes (1.1 MB)
downloaded 1.1 MB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/mime_0.5.zip'
Content type 'application/zip' length 38033 bytes (37 KB)
downloaded 37 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/curl_2.6.zip'
Content type 'application/zip' length 3092980 bytes (2.9 MB)
downloaded 2.9 MB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/openssl_0.9.6.zip'
Content type 'application/zip' length 3568264 bytes (3.4 MB)
downloaded 3.4 MB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/bitops_1.0-6.zip'
Content type 'application/zip' length 37218 bytes (36 KB)
downloaded 36 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/stringr_1.2.0.zip'
Content type 'application/zip' length 148357 bytes (144 KB)
downloaded 144 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/testthat_1.0.2.zip'
Content type 'application/zip' length 1055239 bytes (1.0 MB)
downloaded 1.0 MB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/httr_1.2.1.zip'
Content type 'application/zip' length 280260 bytes (273 KB)
downloaded 273 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/yaml_2.1.14.zip'
Content type 'application/zip' length 179623 bytes (175 KB)
downloaded 175 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/RCurl_1.95-4.8.zip'
Content type 'application/zip' length 2870687 bytes (2.7 MB)
downloaded 2.7 MB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/digest_0.6.12.zip'
Content type 'application/zip' length 172985 bytes (168 KB)
downloaded 168 KB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/stringi_1.1.5.zip'
Content type 'application/zip' length 14289534 bytes (13.6 MB)
downloaded 13.6 MB

试开URL’http://cloud.r-project.org/bin/windows/contrib/3.4/swirl_2.4.3.zip'
Content type 'application/zip' length 235617 bytes (230 KB)
downloaded 230 KB

程序包‘magrittr’打开成功，MD5和检查也通过
程序包‘crayon’打开成功，MD5和检查也通过
程序包‘praise’打开成功，MD5和检查也通过
程序包‘R6’打开成功，MD5和检查也通过
程序包‘jsonlite’打开成功，MD5和检查也通过
程序包‘mime’打开成功，MD5和检查也通过
程序包‘curl’打开成功，MD5和检查也通过
程序包‘openssl’打开成功，MD5和检查也通过
程序包‘bitops’打开成功，MD5和检查也通过
程序包‘stringr’打开成功，MD5和检查也通过
程序包‘testthat’打开成功，MD5和检查也通过
程序包‘httr’打开成功，MD5和检查也通过
程序包‘yaml’打开成功，MD5和检查也通过
程序包‘RCurl’打开成功，MD5和检查也通过
程序包‘digest’打开成功，MD5和检查也通过
程序包‘stringi’打开成功，MD5和检查也通过
程序包‘swirl’打开成功，MD5和检查也通过

下载的二进制程序包在
        C:\Users\nasca\AppData\Local\Temp\RtmpIN3zxf\downloaded_packages里
> 
