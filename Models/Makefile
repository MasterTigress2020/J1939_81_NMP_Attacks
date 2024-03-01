all:
	nuXmv -source commands single-address-claim.smv > result_single
	nuXmv -source commands arbitrary-address-claim.smv > result_arbitrary
	$(info This model takes considerable more time --around 8-9 mins-- to run. Be patient.)
	nuXmv -source commands command-configurable.smv > result_command_configurable
	$(info Formal verification output has been saved in result_single, result_arbitrary, result_command_configurable files)

single:
	nuXmv -source commands single-address-claim.smv > result_single
	$(info Formal verification output has been saved in result_single)


arbitrary:
	nuXmv -source commands arbitrary-address-claim.smv > result_arbitrary
	$(info Formal verification output has been saved in result_arbitrary)

command_configurable:
	$(info This model takes considerable more time around --8-9 mins-- to run. Be patient.)
	nuXmv -source commands command-configurable.smv > result_command_configurable
	$(info Formal verification output has been saved in result_command_configurable)
clean:
	@rm -rf result_single result_arbitrary result_command_configurable
