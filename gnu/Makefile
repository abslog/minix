#	$NetBSD: Makefile,v 1.17 2010/12/03 21:38:47 plunky Exp $

.if defined(__MINIX)
SUBDIR+= dist .WAIT
.endif # defined(__MINIX)
SUBDIR+= usr.bin

# Speedup stubs for some subtrees that don't need to run these rules
includes-libexec:
	@true

.include <bsd.subdir.mk>
