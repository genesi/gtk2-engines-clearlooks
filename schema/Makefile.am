xmldir = $(pkgdatadir)

EXTRA_DIST= clearlooks.xml.in.in

xml_DATA = $(BUILD_SCHEMAS)
xml_in_files = $(xml_DATA:.xml=.xml.in)
xml_in_in_files = $(xml_DATA:.xml=.xml.in.in)

@INTLTOOL_XML_RULE@

CLEANFILES = $(xml_DATA) $(xml_in_files)

-include $(top_srcdir)/git.mk

