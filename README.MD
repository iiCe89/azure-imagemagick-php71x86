![](https://img.shields.io/badge/platform-Azure-00abec.svg?style=flat-square)
![](https://img.shields.io/badge/PHP-7.1-4F5B93.svg?style=flat-square)
![](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)

# ImageMagick for php 7.1 x86 on Azure

SiteExtension for Azure with PHP 7.1 x86

It contains: 
- ImageMagick 7.0.7-27-Q16-x88
- PECL imagick 3.4.3 (PHP 7.1 NTS x86)

### Installation

Install extension through KUDU SCM console

If you already have custom PATH in your .xd file add below to it to make ImageMagick work:

%PATH%%HOME%\SiteExtensions\ImageMagickPHP71x86\lib;

Environment Variables added by this package
- MAGICK_CODER_MODULE_PATH
- MAGICK_CODER_FILTER_PATH
- MAGICK_HOME
- MAGICK_CONFIGURE_PATH