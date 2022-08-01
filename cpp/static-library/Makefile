GRADLE_OPTS = --console=plain

build:
	gradle $(GRADLE_OPTS) assemble

run:
	LD_LIBRARY_PATH=list/build/lib/main/debug/shared app/build/exe/main/debug/app

clean:
	gradle clean
