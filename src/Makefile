test:
	raco test sicp

lint:
	@echo "check codestyle"
	@(for f in $$(find sicp -name '*.rkt'); do raco review $$f; done)



install:
	raco pkg install sicp
	raco pkg install review

.PHONY: test