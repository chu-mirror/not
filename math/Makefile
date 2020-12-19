essay = finite-calculus 
elements = summation

pdfs = $(essay:=.pdf)
logs = $(essay:=.log)

epdfs = $(elements:=.pdf)
elogs = $(elements:=.log)

clean:
	rm -f $(pdfs) $(logs)

clean-elements:
	cd elements && rm -f $(epdfs) $(elogs)

clean-all: clean clean-elements


