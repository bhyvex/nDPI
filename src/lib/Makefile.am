bin_PROGRAMS = ndpi_network_list_compile
AM_CPPFLAGS = -I$(top_srcdir)/src/include/  -I$(top_srcdir)/src/lib/third_party/include/

lib_LTLIBRARIES = libndpi.la

CFLAGS += -fPIC -DPIC -DNDPI_LIB_COMPILATION # --coverage
libndpi_la_CPPFLAGS = -I$(top_srcdir)/src/include/  -I$(top_srcdir)/src/lib/third_party/include/ @HS_INC@
libndpi_la_LDFLAGS = -version-info 1:0:0 -export-symbols $(top_srcdir)/libndpi.sym

libndpi_la_includedir = $(includedir)/libndpi-@VERSION@/libndpi

BUILT_SOURCES = ndpi_network_list.c.inc

libndpi_la_include_HEADERS = ../include/ndpi_api.h \
			     ../include/ndpi_define.h \
			     ../include/ndpi_main.h \
			     ../include/ndpi_includes.h \
			     ../include/ndpi_config.h       \
			     ../include/ndpi_protocol_ids.h \
			     ../include/ndpi_protocols.h    \
			     ../include/ndpi_typedefs.h     \
			     third_party/include/libcache.h

libndpi_la_SOURCES = ndpi_content_match.c.inc \
		     ndpi_network_list.c.inc \
		     ndpi_main.c \
		     protocols/afp.c \
		     protocols/ajp.c \
		     protocols/aimini.c \
		     protocols/applejuice.c \
		     protocols/apple_push.c \
		     protocols/armagetron.c \
		     protocols/ayiya.c \
		     protocols/amqp.c \
		     protocols/battlefield.c \
		     protocols/bgp.c \
		     protocols/bittorrent.c \
		     protocols/bjnp.c \
		     protocols/checkmk.c \
		     protocols/ciscovpn.c \
		     protocols/citrix.c \
		     protocols/coap.c \
		     protocols/collectd.c \
		     protocols/corba.c \
		     protocols/crossfire.c \
		     protocols/csgo.c \
		     protocols/dcerpc.c \
		     protocols/dhcp.c \
		     protocols/dhcpv6.c \
		     protocols/diameter.c \
		     protocols/directconnect.c \
		     protocols/directdownloadlink.c \
		     protocols/dns.c \
		     protocols/dofus.c \
		     protocols/drda.c \
		     protocols/dropbox.c \
		     protocols/eaq.c \
		     protocols/edonkey.c \
		     protocols/fasttrack.c \
		     protocols/fbzero.c \
		     protocols/fiesta.c \
		     protocols/fix.c \
		     protocols/florensia.c \
		     protocols/ftp_control.c \
		     protocols/ftp_data.c \
		     protocols/git.c \
		     protocols/gnutella.c \
		     protocols/gtp.c \
		     protocols/guildwars.c \
		     protocols/hangout.c \
		     protocols/h323.c \
		     protocols/halflife2_and_mods.c \
		     protocols/hep.c \
		     protocols/http_activesync.c \
		     protocols/http.c \
		     protocols/iax.c \
		     protocols/icecast.c \
		     protocols/ipp.c \
		     protocols/irc.c \
		     protocols/jabber.c \
		     protocols/kakaotalk_voice.c \
		     protocols/kerberos.c \
		     protocols/kontiki.c \
		     protocols/ldap.c \
		     protocols/lotus_notes.c \
		     protocols/lisp.c \
		     protocols/mail_imap.c \
		     protocols/mail_pop.c \
		     protocols/mail_smtp.c \
		     protocols/maplestory.c \
		     protocols/mdns.c \
		     protocols/megaco.c \
		     protocols/mgcp.c \
		     protocols/mpegts.c \
		     protocols/mqtt.c \
		     protocols/msn.c \
		     protocols/mssql_tds.c \
		     protocols/mysql.c \
		     protocols/netbios.c \
		     protocols/netflow.c \
		     protocols/nintendo.c \
		     protocols/nfs.c \
		     protocols/noe.c \
		     protocols/non_tcp_udp.c \
		     protocols/ntp.c \
		     protocols/openft.c \
		     protocols/openvpn.c \
		     protocols/oracle.c \
		     protocols/oscar.c \
		     protocols/pando.c \
		     protocols/pcanywhere.c \
		     protocols/postgres.c \
		     protocols/pplive.c \
		     protocols/ppstream.c \
		     protocols/pptp.c \
		     protocols/qq.c \
		     protocols/quic.c \
		     protocols/radius.c \
		     protocols/rdp.c \
		     protocols/redis_net.c \
		     protocols/rsync.c \
		     protocols/rtcp.c \
		     protocols/rtmp.c \
		     protocols/rtp.c \
		     protocols/rtsp.c \
		     protocols/rx.c \
		     protocols/sflow.c \
		     protocols/shoutcast.c \
		     protocols/sip.c \
		     protocols/skinny.c \
		     protocols/skype.c \
		     protocols/smb.c \
		     protocols/snmp.c \
		     protocols/socks45.c \
		     protocols/sopcast.c \
		     protocols/soulseek.c \
		     protocols/spotify.c \
		     protocols/ssdp.c \
		     protocols/ssh.c \
		     protocols/ssl.c \
		     protocols/starcraft.c \
		     protocols/stealthnet.c \
		     protocols/steam.c \
		     protocols/stun.c \
		     protocols/syslog.c \
		     protocols/tcp_udp.c \
		     protocols/teamspeak.c \
		     protocols/teamviewer.c \
		     protocols/telegram.c \
		     protocols/telnet.c \
		     protocols/tftp.c \
		     protocols/thunder.c \
		     protocols/tor.c \
		     protocols/teredo.c \
		     protocols/tvants.c \
		     protocols/tvuplayer.c \
		     protocols/ubntac2.c \
		     protocols/usenet.c \
		     protocols/viber.c \
		     protocols/vhua.c \
		     protocols/vmware.c \
		     protocols/vnc.c \
		     protocols/warcraft3.c \
		     protocols/whoisdas.c \
		     protocols/world_of_kung_fu.c \
		     protocols/world_of_warcraft.c \
		     protocols/xbox.c \
		     protocols/xdmcp.c \
		     protocols/yahoo.c \
		     protocols/zattoo.c \
		     protocols/zeromq.c \
		     protocols/smpp.c \
		     protocols/tinc.c \
		     protocols/someip.c \
		     protocols/whatsapp.c \
		     third_party/include/actypes.h \
		     third_party/include/ahocorasick.h \
		     third_party/include/ndpi_patricia.h \
		     third_party/include/node.h \
		     third_party/include/sort.h \
		     third_party/include/libcache.h \
		     third_party/src/ahocorasick.c \
		     third_party/src/node.c \
		     third_party/src/sort.c \
		     third_party/src/libcache.c

EXTRA_DIST = third_party/src/ndpi_patricia.c

PROTO_CFG_FILES = $(wildcard ndpi_network_list_*.yaml)

ndpi_network_list.c.inc: $(PROTO_CFG_FILES) ndpi_network_list_compile
		./ndpi_network_list_compile -o $@ $(PROTO_CFG_FILES)

