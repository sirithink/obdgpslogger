INCLUDE_DIRECTORIES(
	.
)


FILE(GLOB OBDCOMM_SRCS
	*.c *.h
)

ADD_LIBRARY(ckobdcomm STATIC ${OBDCOMM_SRCS})

