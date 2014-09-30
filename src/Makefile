INTERFACES=sql_base.cmi sql_types.cmi sql_parsers.cmi sql_keywords.cmi \
		sql_printers.cmi sql_builders.cmi sql_public.cmi \
		inner_sql.cmi \
		sql.cmi check.cmi query.cmi \

TARGETS=pa_macaque.cmo pa_bananas.cmo macaque.cma macaque.cmxa macaque.cmxs

all:
	cd .. && make
install:
	ocamlfind install macaque META $(addprefix ../_build/src/,$(INTERFACES) $(TARGETS))
