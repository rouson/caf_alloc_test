CAF=ftn

executable:=crash
$(executable): main.f90 Makefile
	$(CAF) $< -o $@

.PHONY: clean
clean:
	rm $(executable) *.dot
