# =========================================================================
#     This makefile was generated by
#     Bakefile 0.2.9 (http://www.bakefile.org)
#     Do not modify, all changes will be overwritten!
# =========================================================================




prefix = /usr/local
exec_prefix = ${prefix}
datarootdir = ${prefix}/share
INSTALL = /usr/bin/install -c
EXEEXT = 
WINDRES = 
SETFILE = SetFile
NM = nm
BK_DEPS = /Users/jhg/Documents/work/mog-master/M4/wxWidgets-3.0.2/build-cocoa-debug/bk-deps
srcdir = ../../../samples/help
top_srcdir = ../../..
LIBS = -lz -lpthread -lc++
LDFLAGS_GUI = 
CXX = g++ -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.9.sdk -mmacosx-version-min=10.7
CXXFLAGS = -DWX_PRECOMP -O2 -fno-strict-aliasing -std=c++0x -stdlib=libc++ -fno-common 
CPPFLAGS = -D_FILE_OFFSET_BITS=64 -I${wx_top_builddir}/lib/wx/include/osx_cocoa-unicode-static-3.0 -I${top_srcdir}/include -stdlib=libc++
LDFLAGS =   -framework IOKit -framework Carbon -framework Cocoa -framework AudioToolbox -framework System -framework OpenGL 
WX_LIB_FLAVOUR = 
TOOLKIT = OSX_COCOA
TOOLKIT_LOWERCASE = osx_cocoa
TOOLKIT_VERSION = 
TOOLCHAIN_FULLNAME = osx_cocoa-unicode-static-3.0
EXTRALIBS =   -framework IOKit -framework Carbon -framework Cocoa -framework AudioToolbox -framework System -framework OpenGL  -lz -lpthread -lc++ 
EXTRALIBS_XML =  -lexpat
EXTRALIBS_HTML = 
EXTRALIBS_GUI = 
EXTRALIBS_SDL = 
CXXWARNINGS = -Wall -Wundef -Wunused-parameter -Wno-ctor-dtor-privacy -Woverloaded-virtual -Wno-deprecated-declarations
HOST_SUFFIX = 
SAMPLES_RPATH_FLAG = 
wx_top_builddir = /Users/jhg/Documents/work/mog-master/M4/wxWidgets-3.0.2/build-cocoa-debug

### Variables: ###

DESTDIR = 
WX_RELEASE = 3.0
WX_VERSION = $(WX_RELEASE).2
LIBDIRNAME = $(wx_top_builddir)/lib
HELP_CXXFLAGS = -D__WX$(TOOLKIT)__ $(__WXUNIV_DEFINE_p) $(__DEBUG_DEFINE_p) \
	$(__EXCEPTIONS_DEFINE_p) $(__RTTI_DEFINE_p) $(__THREAD_DEFINE_p) \
	-I$(srcdir) $(__DLLFLAG_p) -I$(srcdir)/../../samples $(CXXWARNINGS) \
	$(CPPFLAGS) $(CXXFLAGS)
HELP_OBJECTS =  \
	$(__help___win32rc) \
	$(__help_os2_lib_res) \
	help_demo.o

### Conditionally set variables: ###

#CXXC = $(CXX)
CXXC = $(BK_DEPS) $(CXX)
PLUGIN_ADV_EXTRALIBS = $(EXTRALIBS_SDL)
#PORTNAME = base
PORTNAME = $(TOOLKIT_LOWERCASE)$(TOOLKIT_VERSION)
#WXBASEPORT = _carbon
#WXDEBUGFLAG = d
WXUNICODEFLAG = u
#WXUNIVNAME = univ
#EXTRALIBS_FOR_BASE = $(EXTRALIBS)
EXTRALIBS_FOR_BASE = $(EXTRALIBS) \
	$(EXTRALIBS_XML) $(EXTRALIBS_GUI)
#EXTRALIBS_FOR_GUI = $(EXTRALIBS_GUI)
EXTRALIBS_FOR_GUI = 
#__help___mac_setfilecmd = @true
__help___mac_setfilecmd = \
	$(SETFILE) -t APPL help$(EXEEXT)
#__WXUNIV_DEFINE_p = -D__WXUNIVERSAL__
#__WXUNIV_DEFINE_p_2 = --define __WXUNIVERSAL__
#__DEBUG_DEFINE_p = -DwxDEBUG_LEVEL=0
#__DEBUG_DEFINE_p_2 = --define wxDEBUG_LEVEL=0
#__EXCEPTIONS_DEFINE_p = -DwxNO_EXCEPTIONS
#__EXCEPTIONS_DEFINE_p_2 = --define wxNO_EXCEPTIONS
#__RTTI_DEFINE_p = -DwxNO_RTTI
#__RTTI_DEFINE_p_2 = --define wxNO_RTTI
#__THREAD_DEFINE_p = -DwxNO_THREADS
#__THREAD_DEFINE_p_2 = --define wxNO_THREADS
#__DLLFLAG_p = -DWXUSINGDLL
#__DLLFLAG_p_2 = --define WXUSINGDLL
COND_PLATFORM_OS2_1___help___os2_emxbindcmd = $(NM) help$(EXEEXT) | if grep -q \
	pmwin.763 ; then emxbind -ep help$(EXEEXT) ; fi
#__help___os2_emxbindcmd = $(COND_PLATFORM_OS2_1___help___os2_emxbindcmd)
#__RCDEFDIR_p_1 = --include-dir \
#	$(LIBDIRNAME)/wx/include/$(TOOLCHAIN_FULLNAME)
#__help___win32rc = help_sample_rc.o
#__help_os2_lib_res = \
#	$(top_srcdir)/include/wx/os2/wx.res
__help_app_Contents_PkgInfo___depname \
	= help.app/Contents/PkgInfo
__help_bundle___depname = help_bundle
#____help_BUNDLE_TGT_REF_DEP = \
#	$(__help_app_Contents_PkgInfo___depname)
#____help_BUNDLE_TGT_REF_DEP \
#	= $(__help_app_Contents_PkgInfo___depname)
____help_BUNDLE_TGT_REF_DEP \
	= $(__help_app_Contents_PkgInfo___depname)
#____help_BUNDLE_TGT_REF_DEP \
#	= $(__help_app_Contents_PkgInfo___depname)
#____help_BUNDLE_TGT_REF_DEP = \
#	$(__help_app_Contents_PkgInfo___depname)
COND_MONOLITHIC_0___WXLIB_HTML_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)_html-$(WX_RELEASE)$(HOST_SUFFIX)
#__WXLIB_HTML_p = $(COND_MONOLITHIC_0___WXLIB_HTML_p)
COND_MONOLITHIC_0___WXLIB_ADV_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)_adv-$(WX_RELEASE)$(HOST_SUFFIX)
#__WXLIB_ADV_p = $(COND_MONOLITHIC_0___WXLIB_ADV_p)
COND_MONOLITHIC_0___WXLIB_CORE_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)_core-$(WX_RELEASE)$(HOST_SUFFIX)
#__WXLIB_CORE_p = $(COND_MONOLITHIC_0___WXLIB_CORE_p)
COND_MONOLITHIC_0___WXLIB_BASE_p = \
	-lwx_base$(WXBASEPORT)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
#__WXLIB_BASE_p = $(COND_MONOLITHIC_0___WXLIB_BASE_p)
COND_MONOLITHIC_1___WXLIB_MONO_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__WXLIB_MONO_p = $(COND_MONOLITHIC_1___WXLIB_MONO_p)
__LIB_SCINTILLA_IF_MONO_p \
	= \
	-lwxscintilla$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_TIFF_p \
	= \
	-lwxtiff$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_JPEG_p \
	= \
	-lwxjpeg$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_PNG_p \
	= \
	-lwxpng$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
#__LIB_ZLIB_p = \
#	-lwxzlib$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
COND_wxUSE_REGEX_builtin___LIB_REGEX_p = \
	-lwxregex$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_REGEX_p = $(COND_wxUSE_REGEX_builtin___LIB_REGEX_p)
#__LIB_EXPAT_p = \
#	-lwxexpat$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)

### Targets: ###

all: help$(EXEEXT) $(__help_bundle___depname) data data_doc

install: 

uninstall: 

install-strip: install

clean: 
	rm -rf ./.deps ./.pch
	rm -f ./*.o
	rm -f help$(EXEEXT)
	rm -rf help.app

distclean: clean
	rm -f config.cache config.log config.status bk-deps bk-make-pch shared-ld-sh Makefile

help$(EXEEXT): $(HELP_OBJECTS) $(__help___win32rc)
	$(CXX) -o $@ $(HELP_OBJECTS)    -L$(LIBDIRNAME) $(LDFLAGS_GUI) $(SAMPLES_RPATH_FLAG) $(LDFLAGS)  $(__WXLIB_HTML_p) $(EXTRALIBS_HTML) $(__WXLIB_ADV_p) $(PLUGIN_ADV_EXTRALIBS) $(__WXLIB_CORE_p)  $(__WXLIB_BASE_p)  $(__WXLIB_MONO_p) $(__LIB_SCINTILLA_IF_MONO_p) $(__LIB_TIFF_p) $(__LIB_JPEG_p) $(__LIB_PNG_p)  $(EXTRALIBS_FOR_GUI) $(__LIB_ZLIB_p) $(__LIB_REGEX_p) $(__LIB_EXPAT_p) $(EXTRALIBS_FOR_BASE) $(LIBS)
	
	$(__help___mac_setfilecmd)
	$(__help___os2_emxbindcmd)

help.app/Contents/PkgInfo: help$(EXEEXT) $(top_srcdir)/src/osx/carbon/Info.plist.in $(top_srcdir)/src/osx/carbon/wxmac.icns
	mkdir -p help.app/Contents
	mkdir -p help.app/Contents/MacOS
	mkdir -p help.app/Contents/Resources
	
	
	sed -e "s/IDENTIFIER/`echo $(srcdir) | sed -e 's,\.\./,,g' | sed -e 's,/,.,g'`/" \
	-e "s/EXECUTABLE/help/" \
	-e "s/VERSION/$(WX_VERSION)/" \
	$(top_srcdir)/src/osx/carbon/Info.plist.in >help.app/Contents/Info.plist
	
	
	/bin/echo "APPL????" >help.app/Contents/PkgInfo
	
	
	ln -f help$(EXEEXT) help.app/Contents/MacOS/help
	
	
	cp -f $(top_srcdir)/src/osx/carbon/wxmac.icns help.app/Contents/Resources/wxmac.icns

help_bundle: $(____help_BUNDLE_TGT_REF_DEP)

data: 
	@mkdir -p .
	@for f in back.gif bullet.bmp contents.gif cshelp.txt doc.chm doc.cnt doc.hhc doc.hhk doc.hhp doc.hlp doc.hpj doc.zip forward.gif up.gif; do \
	if test ! -f ./$$f -a ! -d ./$$f ; \
	then x=yep ; \
	else x=`find $(srcdir)/$$f -newer ./$$f -print` ; \
	fi; \
	case "$$x" in ?*) \
	cp -pRf $(srcdir)/$$f . ;; \
	esac; \
	done

data_doc: 
	@mkdir -p ./doc
	@for f in aindex.html ClassGraph.class ClassGraphPanel.class ClassLayout.class down.gif dxxgifs.tex HIER.html HIERjava.html icon1.gif icon2.gif index.html logo.gif NavigatorButton.class USE_HELP.html wx204.htm wx34.htm wxExtHelpController.html wxhelp.map wx.htm; do \
	if test ! -f ./doc/$$f -a ! -d ./doc/$$f ; \
	then x=yep ; \
	else x=`find $(srcdir)/doc/$$f -newer ./doc/$$f -print` ; \
	fi; \
	case "$$x" in ?*) \
	cp -pRf $(srcdir)/doc/$$f ./doc ;; \
	esac; \
	done

help_sample_rc.o: $(srcdir)/../../samples/sample.rc
	$(WINDRES) -i$< -o$@    --define __WX$(TOOLKIT)__ $(__WXUNIV_DEFINE_p_2) $(__DEBUG_DEFINE_p_2)  $(__EXCEPTIONS_DEFINE_p_2) $(__RTTI_DEFINE_p_2) $(__THREAD_DEFINE_p_2)   --include-dir $(srcdir) $(__DLLFLAG_p_2) --include-dir $(srcdir)/../../samples $(__RCDEFDIR_p_1) --include-dir $(top_srcdir)/include

help_demo.o: $(srcdir)/demo.cpp
	$(CXXC) -c -o $@ $(HELP_CXXFLAGS) $(srcdir)/demo.cpp


# Include dependency info, if present:
-include ./.deps/*.d

.PHONY: all install uninstall clean distclean help_bundle data data_doc
