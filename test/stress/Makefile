#################################################
#          IncludeOS SERVICE makefile           #
#################################################

# The name of your service
SERVICE = stresstest
SERVICE_NAME = IncludeOS stress test

# Your service parts
FILES = service.cpp

LOCAL_INCLUDES=-I$(shell pwd)/../lest/include/lest

# Your disk image
DISK=

# IncludeOS location
ifndef INCLUDEOS_INSTALL
INCLUDEOS_INSTALL=$(HOME)/IncludeOS_install
endif

include $(INCLUDEOS_INSTALL)/Makeseed
