export MakeInc_cmd=${SRCROOT}/makedefs/MakeInc.cmd
export MakeInc_def=${SRCROOT}/makedefs/MakeInc.def
export MakeInc_rule=${SRCROOT}/makedefs/MakeInc.rule
export MakeInc_dir=${SRCROOT}/makedefs/MakeInc.dir

include $(MakeInc_cmd)
include $(MakeInc_def)

INSTINC_SUBDIRS = \
	libkern \
	uuid
INSTINC_SUBDIRS_I386 = ${INSTINC_SUBDIRS}
INSTINC_SUBDIRS_X86_64 = ${INSTINC_SUBDIRS}
INSTINC_SUBDIRS_ARM = ${INSTINC_SUBDIRS}

EXPINC_SUBDIRS = \
	libkern \
	uuid
EXPINC_SUBDIRS_I386 = ${EXPINC_SUBDIRS}
EXPINC_SUBDIRS_X86_64 = ${EXPINC_SUBDIRS}
EXPINC_SUBDIRS_ARM = ${EXPINC_SUBDIRS}

SETUP_SUBDIRS =

COMP_SUBDIRS_I386 = conf
COMP_SUBDIRS_X86_64 = conf
COMP_SUBDIRS_ARM = conf


INST_SUBDIRS = 

include $(MakeInc_rule)
include $(MakeInc_dir)
