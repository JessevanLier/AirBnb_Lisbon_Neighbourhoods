TEMP = ../../gen/temp
PREP = ../../src/data-preparation

all: directory $(TEMP)

directory: $(PREP)

$(TEMP)
        R --vanilla < $(PREP)/holidaydata_eu.R
