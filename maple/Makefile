
###############################################################################
# MODULE     : Make file for maple plugin
# COPYRIGHT  : (C) 1999-2008  Joris van der Hoeven
###############################################################################
# This software falls under the GNU general public license version 3 or later.
# It comes WITHOUT ANY WARRANTY WHATSOEVER. For details, see the file LICENSE
# in the root directory or <http://www.gnu.org/licenses/gpl-3.0.html>.
###############################################################################

CC = gcc
CXX = g++
RM = rm -f

all: bin/tm_maple_5

bin/tm_maple_5: src/tm_maple_5.cpp
	$(CXX) $(CPPFLAGS) $(CXXFLAGS) src/tm_maple_5.cpp -o bin/tm_maple_5

clean:
	$(RM) *~
	$(RM) */*~
	$(RM) bin/tm_maple_5
	$(RM) $(HOME)/.TeXmacs/bin/tm_maple_9.sh
	$(RM) $(HOME)/.TeXmacs/bin/tm_maple_9
