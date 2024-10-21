CIM_TRIG = d:/Onto/proj/electrical/ENTSOE-SHACL/Inst4CIM-KG/rdf-improved/cim-trig.pl
IGNORE = CDPSM_2_0/Nordic44_CPSM_01_MF.xml CDPSM_2_0/Nordic44_03_inc.xml CGMES_2_4/Nordic44_CGM_36f_MF.xml CGMES_2_4/Nordic44_CGM_38_CO.xml
RDF = $(filter-out $(IGNORE), $(wildcard *_2_*/*.xml))
TRIG = $(patsubst %.xml,%.trig, $(RDF))

.PHONY: all clean

all: $(TRIG)

clean::
	rm -f $(TRIG)

%.trig: %.xml
	perl $(CIM_TRIG) $^ $@
