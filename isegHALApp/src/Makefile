TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += devisegHAL

# xxxRecord.h will be created from xxxRecord.dbd
#DBDINC += xxxRecord
# install devisegHAL.dbd into <top>/dbd
DBD += devIsegHal.dbd

# specify all source files to be compiled and added to the library
#devisegHAL_SRCS += xxx
devisegHAL_SRCS += devIsegHalAi.c devIsegHalGlobalSwitchBo.c devIsegHalMbbid.c devIsegHalAo.c devIsegHalStringin.c devIsegHal.cpp devIsegHalLi.c devIsegHalAsync.c devIsegHalBo.c devIsegHalLo.c devIsegHalBi.c devIsegHalStringout.c

devisegHAL_LIBS += $(EPICS_BASE_IOC_LIBS)
devisegHAL_SYS_LIBS += isegHAL-client

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

