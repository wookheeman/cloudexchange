#
# Copyright (c) 2010-2013 NEC Corporation
# All rights reserved.
# 
# This program and the accompanying materials are made available under the
# terms of the Eclipse Public License v1.0 which accompanies this
# distribution, and is available at http://www.eclipse.org/legal/epl-v10.html
#

##
## Makefile that drives the production of PFC build tools.
##

SUBDIRS		= src

include ../build/subdirs.mk

distclean:	$(SUBDIRS_ALL)
	$(RM) -rf bin lib man

distclean:	SUBDIRS_TARGET = distclean
