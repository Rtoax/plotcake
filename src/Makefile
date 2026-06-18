CFLAGS += $(shell pkg-config --cflags ncursesw)
LDFLAGS += $(shell pkg-config --libs ncursesw)
LDFLAGS += -lm

plotcake: plotcake.o load.o plot.o ram.o stdin.o value.o lines.o keyboard.o \
	file.o utils.o
