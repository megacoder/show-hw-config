HOST	:=$(shell /bin/hostname)

${HOST}::
	sudo ../show-hw-config >${HOST}

clean::

distclean clobber:: clean
	${RM} ${HOST}
