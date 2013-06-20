#SWF_COMPILER = ~/Downloads/flex_sdk/bin/mxmlc
SWF_COMPILER = mxmlc
#OUTPUT = /nail/home/buck/pg/3/htdocs/html/flash/swfupload.swf
OUTPUT = swfupload.swf

DEBUG = 0
ifeq ($(DEBUG), 1)
	DEBUG = -debug
else
	DEBUG = 
endif

all:
	$(SWF_COMPILER) -static-link-runtime-shared-libraries $(DEBUG) -default-size 300 300 -default-frame-rate 15 SWFUpload.as -output $(OUTPUT)
