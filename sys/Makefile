ifneq (,$(filter posix_semaphore,$(USEMODULE)))
    DIRS += posix/semaphore
endif
ifneq (,$(filter posix_sockets,$(USEMODULE)))
    DIRS += posix/sockets
endif
ifneq (,$(filter pthread,$(USEMODULE)))
    DIRS += posix/pthread
endif
ifneq (,$(filter shell_commands,$(USEMODULE)))
    DIRS += shell/commands
endif
ifneq (,$(filter net_help,$(USEMODULE)))
    DIRS += net/crosslayer/net_help
endif
ifneq (,$(filter routing,$(USEMODULE)))
    DIRS += net/routing
endif
ifneq (,$(filter oneway_malloc,$(USEMODULE)))
    DIRS += oneway-malloc
endif
ifneq (,$(filter ieee802154,$(USEMODULE)))
    DIRS += net/link_layer/ieee802154
endif
ifneq (,$(filter ipv4_addr,$(USEMODULE)))
    DIRS += net/network_layer/ipv4/addr
endif
ifneq (,$(filter ipv6_addr,$(USEMODULE)))
    DIRS += net/network_layer/ipv6/addr
endif
ifneq (,$(filter ipv6_ext_rh,$(USEMODULE)))
    DIRS += net/network_layer/ipv6/ext/rh
endif
ifneq (,$(filter ipv6_ext,$(USEMODULE)))
    DIRS += net/network_layer/ipv6/ext
endif
ifneq (,$(filter ipv6_hdr,$(USEMODULE)))
    DIRS += net/network_layer/ipv6/hdr
endif
ifneq (,$(filter gnrc gnrc_%,$(USEMODULE)))
    DIRS += net/gnrc
endif
ifneq (,$(filter inet_csum,$(USEMODULE)))
    DIRS += net/crosslayer/inet_csum
endif
ifneq (,$(filter cipher_modes,$(USEMODULE)))
    DIRS += crypto/modes
endif
ifneq (,$(filter nhdp,$(USEMODULE)))
    DIRS += net/routing/nhdp
endif
ifneq (,$(filter gnrc_netdev2,$(USEMODULE)))
    DIRS += net/gnrc/link_layer/netdev2
endif
ifneq (,$(filter fib,$(USEMODULE)))
    DIRS += net/network_layer/fib
endif
ifneq (,$(filter sixlowpan,$(USEMODULE)))
    DIRS += net/network_layer/sixlowpan
endif
ifneq (,$(filter log_%,$(USEMODULE)))
    DIRS += log
endif
ifneq (,$(filter vtimer,$(USEMODULE)))
    DIRS += compat/vtimer
endif
ifneq (,$(filter cpp11-compat,$(USEMODULE)))
    DIRS += cpp11-compat
endif
ifneq (,$(filter udp,$(USEMODULE)))
    DIRS += net/transport_layer/udp
endif

ifneq (,$(filter hamming256,$(USEMODULE)))
    DIRS += ecc/hamming256
endif

ifneq (,$(filter netopt,$(USEMODULE)))
    DIRS += net/crosslayer/netopt
endif
ifneq (,$(filter sema,$(USEMODULE)))
    DIRS += sema
endif

DIRS += $(dir $(wildcard $(addsuffix /Makefile, ${USEMODULE})))

include $(RIOTBASE)/Makefile.base
