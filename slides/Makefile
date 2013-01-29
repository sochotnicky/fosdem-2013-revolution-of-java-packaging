# targets
all: slides.pp.pdf slides.notes.pdf
handout: slides.handout.pdf
notes: slides.notes.pdf
# sample.text.pdf -- don't build article version by default

TEXINPUTS=.:$(RHBEAMER):
export TEXINPUTS

# path to rh beamer
RHBEAMER=..

# common tex makefile
include $(RHBEAMER)/Makefile.common
