srcdir = .
bindir = /usr/local/bin
confdir = /etc/
sharedir = /usr/share/mokopedia/

INSTALL = /usr/bin/install
INSTALLDATA = /usr/bin/install -m 644
INSTALLDIR = /usr/bin/install -m 644 -d

install:
		$(INSTALLDATA) mokopedia.cfg $(confdir)
		mkdir -p $(sharedir)
		$(INSTALLDIR) $(srcdir)/de $(sharedir)
