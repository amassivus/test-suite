list(APPEND LDFLAGS -lm)
list(APPEND CFLAGS -std=gnu99)
set(RUN_OPTIONS 4160 5)
llvm_multisource(Expansion-flt)
