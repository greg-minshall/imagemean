# $Id: fba8f98c312c5ae3a0a0bffd7bbedd95612a9b89 $

bin_PROGRAMS = imagemean imagehist imagergb
imagemean_SOURCES = imagemean.c imagesubr.c
imagehist_SOURCES = imagehist.c imagesubr.c
imagergb_SOURCES = imagergb.c imagesubr.c

AM_CPPFLAGS = ${IMLIB2_CFLAGS} ${MAGICKWAND_CFLAGS} ${X11_CFLAGS}
AM_LDFLAGS = ${IMLIB2_LIBS} ${MAGICKWAND_LIBS} ${X11_LIBS}