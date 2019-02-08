TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += devisegHAL

# install devisegHAL.dbd into <top>/dbd
DBD += devIsegHal.dbd

# specify all source files to be compiled and added to the library
devisegHAL_SRCS += devIsegHalAi.c
devisegHAL_SRCS += devIsegHalGlobalSwitchBo.c
devisegHAL_SRCS += devIsegHalMbbid.c
devisegHAL_SRCS += devIsegHalAo.c
devisegHAL_SRCS += devIsegHalStringin.c
devisegHAL_SRCS += devIsegHal.cpp
devisegHAL_SRCS += devIsegHalLi.c
devisegHAL_SRCS += devIsegHalAsync.c
devisegHAL_SRCS += devIsegHalBo.c
devisegHAL_SRCS += devIsegHalLo.c
devisegHAL_SRCS += devIsegHalBi.c
devisegHAL_SRCS += devIsegHalStringout.c

#devisegHAL_SYS_LIBS += isegHAL-client

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

