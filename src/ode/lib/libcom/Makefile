# COPYRIGHT NOTICE
# Copyright (c) 1992, 1991, 1990  
# Open Software Foundation, Inc. 
#  
# Permission is hereby granted to use, copy, modify and freely distribute 
# the software in this file and its documentation for any purpose without 
# fee, provided that the above copyright notice appears in all copies and 
# that both the copyright notice and this permission notice appear in 
# supporting documentation.  Further, provided that the name of Open 
# Software Foundation, Inc. ("OSF") not be used in advertising or 
# publicity pertaining to distribution of the software without prior 
# written permission from OSF.  OSF makes no representations about the 
# suitability of this software for any purpose.  It is provided "as is" 
# without express or implied warranty. 
#  
# Copyright (c) 1992 Carnegie Mellon University 
# All Rights Reserved. 
#  
# Permission to use, copy, modify and distribute this software and its 
# documentation is hereby granted, provided that both the copyright 
# notice and this permission notice appear in all copies of the 
# software, derivative works or modified versions, and any portions 
# thereof, and that both notices appear in supporting documentation. 
#  
# CARNEGIE MELLON ALLOWS FREE USE OF THIS SOFTWARE IN ITS "AS IS" 
# CONDITION.  CARNEGIE MELLON DISCLAIMS ANY LIABILITY OF ANY KIND FOR 
# ANY DAMAGES WHATSOEVER RESULTING FROM THE USE OF THIS SOFTWARE. 
#  
# Carnegie Mellon requests users of this software to return to 
#  
# Software Distribution Coordinator  or  Software_Distribution@CS.CMU.EDU 
# School of Computer Science 
# Carnegie Mellon University 
# Pittsburgh PA 15213-3890 
#  
# any improvements or extensions that they make and grant Carnegie Mellon 
# the rights to redistribute these changes. 
#
# HISTORY
# $Log: Makefile,v $
# Revision 1.1.2.2  1994/06/22  18:51:38  marty
# 	Reorg for encryption
# 	[1994/06/22  18:50:26  marty]
#
# Revision 1.1.2.1  1994/02/17  18:49:38  damon
# 	CR 1056. Moved from ./bin/sup/
# 	[1994/02/17  18:49:29  damon]
# 
# $EndLog$

LIBRARIES		= libcom.a
EXPLIB_TARGETS		= export_libcom.a
EXPDIR			= /usr/lib/
.if exists(crypt.c)
OFILES			= scm.o scmio.o crypt.o
.else
OFILES			= scm.o scmio.o no_crypt.o
.endif
.include <${RULES_MK}>
