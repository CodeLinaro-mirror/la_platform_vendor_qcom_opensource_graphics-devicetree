ifeq ($(CONFIG_ARCH_PINEAPPLE), y)
dtbo-y += gpu/pineapple-gpu.dtbo \
		gpu/pineapple-v2-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_SERAPH), y)
dtbo-y += gpu/seraph-gpu.dtbo \
		gpu/seraph-no-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_SUN), y)
dtbo-y += gpu/sun-gpu.dtbo \
		gpu/sun-v2-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_TUNA), y)
dtbo-y += gpu/tuna-gpu.dtbo \
		gpu/tuna7-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_CANOE), y)
dtbo-y += gpu/canoe-gpu.dtbo \
		gpu/canoe-v2-gpu.dtbo \
		gpu/canoep-sg-gpu.dtbo \
		gpu/canoep-sg-v2-gpu.dtbo \
		gpu/whale-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_X1E80100), y)
dtbo-y += gpu/x1e80100-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_KERA), y)
dtbo-y += gpu/kera-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_ALOR), y)
dtbo-y += gpu/alor-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_ART), y)
dtbo-y += gpu/art-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_PARROT), y)
dtbo-y += gpu/parrot-gpu.dtbo \
		gpu/parrot-sg-gpu.dtbo \
		gpu/parrotp-sg-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_BENGAL), y)
dtbo-y += gpu/bengal-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_KHAJE), y)
dtbo-y += gpu/khaje-gpu.dtbo \
		gpu/khajep-gpu.dtbo \
		gpu/khajeq-gpu.dtbo \
		gpu/khajeg-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_YUPIK), y)
dtbo-y += gpu/yupik-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_CHORA), y)
dtbo-y += gpu/chora-gpu.dtbo
endif

ifeq ($(CONFIG_ARCH_MALABAR), y)
dtbo-y += gpu/malabar-gpu.dtbo
endif

always-y    := $(dtb-y) $(dtbo-y)
subdir-y    := $(dts-dirs)
clean-files    := *.dtb *.dtbo
