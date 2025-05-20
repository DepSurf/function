# Function: <code>__fswab16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81171f52)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/jbd2/commit.c (ffffffff812eaaa3)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812ebdf7)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/ecryptfs/crypto.c (ffffffff8130648e)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_header_metadata
```
```
In fs/nls/nls_base.c (ffffffff8130d38a)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - fs/nls/nls_base.c:utf16s_to_utf8s
  - fs/nls/nls_base.c:utf16s_to_utf8s
  - fs/nls/nls_base.c:utf8s_to_utf16s
  - fs/nls/nls_base.c:utf8s_to_utf16s
  - fs/nls/nls_base.c:utf8s_to_utf16s
  - fs/nls/nls_base.c:utf8s_to_utf16s
```
```
In security/keys/trusted.c (ffffffff81337244)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
```
In security/selinux/hooks.c (ffffffff813443df)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/smack/smack_lsm.c (ffffffff81361a50)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In security/smack/smackfs.c (ffffffff81365a1f)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net6addr
```
```
In security/lsm_audit.c (ffffffff81366202)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/tomoyo/network.c (ffffffff81371e7e)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In security/apparmor/match.c (ffffffff81379163)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/file.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff813915d6)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_prot
  - security/apparmor/af_unix.c:match_to_prot
  - security/apparmor/af_unix.c:profile_listen_perm
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813967be)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In block/partitions/aix.c (ffffffff813cf3c3)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff813cfb94)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff813d0f24)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/sun.c (ffffffff813d35af)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/sysv68.c (ffffffff813d4cc6)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/t10-pi.c (ffffffff813e8821)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_crc_fn
  - block/t10-pi.c:t10_pi_verify
  - block/t10-pi.c:t10_pi_verify
```
```
In lib/decompress_unlzo.c (ffffffff81f9dc04)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/vsprintf.c (ffffffff813f2c0d)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In lib/iomap.c (ffffffff81402847)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16be
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81525bb6)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/lightnvm/sysblk.c (ffffffff81544a35)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/lightnvm/sysblk.c:nvm_sysblk_to_cpu
  - drivers/lightnvm/sysblk.c:nvm_cpu_to_sysblk
```
```
In drivers/base/regmap/regmap.c (ffffffff81562665)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_be
  - drivers/base/regmap/regmap.c:regmap_format_16_be
  - drivers/base/regmap/regmap.c:regmap_format_7_9_write
  - drivers/base/regmap/regmap.c:regmap_format_4_12_write
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff8156a8c7)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
```
```
In drivers/block/virtio_blk.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In drivers/misc/bmp085.c (ffffffff815790c9)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/misc/bmp085.c:bmp085_update_raw_temperature
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
```
```
In drivers/scsi/scsi.c (ffffffff815a64c0)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/sd.c (ffffffff815be0b4)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/scsi/sr.c (ffffffff815c03bf)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In drivers/net/tun.c (ffffffff815ee410)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/virtio_net.c (ffffffff815f3714)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f66a9)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/slip/slhc.c (ffffffff815f8fee)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
```
```
In drivers/cdrom/cdrom.c (ffffffff815fdb42)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fb5822)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
```
```
In net/core/skbuff.c (ffffffff81708fac)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81713f7a)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81725912)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/tso.c (ffffffff81734104)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_start
```
```
In net/core/net-procfs.c (ffffffff81737e09)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738bbd)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff8173b5e8)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_kfree_skb
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_kfree_skb
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
```
```
In net/ethernet/eth.c (ffffffff8173fe49)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
  - net/ethernet/eth.c:eth_header
```
```
In net/802/fc.c (ffffffff8174052c)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/802/fc.c:fc_header
```
```
In net/802/fddi.c (ffffffff8174095c)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_header
```
```
In net/sched/sch_api.c (ffffffff81742d18)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_classify
```
```
In net/netlink/af_netlink.c (ffffffff8174b26f)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/route.c (ffffffff81754e2e)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_input.c (ffffffff81759048)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff8175985d)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175cce8)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762293)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764205)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp_input.c (ffffffff8176be7d)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81774d2a)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ab66)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_pseudoheader
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f124)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817829eb)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/raw.c (ffffffff81785517)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81786983)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/udp_offload.c (ffffffff8178acda)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_del_offload
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:udp_gro_complete
```
```
In net/ipv4/arp.c (ffffffff8178bbc4)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
  - net/ipv4/arp.c:arp_create
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8178efa0)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffff81793268)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff817963c0)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff817a2206)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
```
```
In net/ipv4/ipmr.c (ffffffff817a7432)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/syncookies.c (ffffffff817ab569)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/inet_lro.c (ffffffff817ab9b5)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/inet_lro.c:lro_tcp_ip_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ad6b7)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af961)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff817afce5)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/ipv4/xfrm4_input.c (ffffffff817afecb)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b4bce)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb905)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff817c2be5)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_create
```
```
In net/ipv6/ip6_output.c (ffffffff817c4d93)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff817c8c1f)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff817dea57)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/udp.c (ffffffff817e1a5f)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff817e5db7)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff817e8297)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff817ea28d)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff817edda5)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eeff6)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ping.c (ffffffff817f251f)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff817f52a8)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f73c7)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/ip6mr.c (ffffffff817f8d8c)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff817fca09)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff817fce0b)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/syncookies.c (ffffffff817ff45a)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/exthdrs_core.c (ffffffff817ffcc6)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_checksum.c (ffffffff81800270)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81800ad5)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818022a1)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/ipv6/mcast_snoop.c (ffffffff8180276f)
Location: include/uapi/linux/swab.h:46
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81802bb9)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
```
```
In net/8021q/vlan_core.c (ffffffff818097a4)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817b17)
Location: include/uapi/linux/swab.h:46
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
</details>
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/mmio.c (ffff8000100cde34)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - virt/kvm/arm/mmio.c:io_mem_abort
  - virt/kvm/arm/mmio.c:kvm_handle_mmio_return
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In fs/jbd2/commit.c (ffff8000104ce4b8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d095c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/ecryptfs/crypto.c (ffff8000104f81d0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_header_metadata
```
```
In fs/nls/nls_base.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/keys/trusted.c (ffff80001053a8f0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
```
```
In security/selinux/hooks.c (ffff80001054b27c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/smack/smack_lsm.c (ffff80001056e8e4)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/lsm_audit.c (ffff8000105775b8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In security/tomoyo/network.c (ffff8000105852ec)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/apparmor/match.c (ffff800010590510)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/file.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffff8000105acee4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In block/partitions/aix.c (ffff8000106004ac)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffff800010601130)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffff800010603454)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
```
In block/partitions/sun.c (ffff8000106057bc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/sysv68.c (ffff800010606ee8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/t10-pi.c (ffff80001061ee58)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In block/sed-opal.c (ffff8000106281e0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/sed-opal.c:opal_discovery0_end
  - block/sed-opal.c:opal_discovery0_end
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106ccde8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16be
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010811d68)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_release
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816cc4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:cgr_cleanup
  - drivers/soc/fsl/qbman/qman.c:qpool_cleanup
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_create_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcd58)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd6dc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffff800010911ba4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_be
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/base/regmap/regmap-i2c.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c638)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
```
```
In drivers/scsi/scsi.c (ffff80001096d9c4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_lib.c (ffff800010975394)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
  - drivers/scsi/scsi_lib.c:scsi_vpd_tpg_id
```
```
In drivers/scsi/scsi_trace.c (ffff800010981fa0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/scsi_common.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/scsi/sd.c (ffff800010989f5c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
```
```
In drivers/scsi/sr.c (ffff80001098c4e8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
```
```
In drivers/ata/libata-scsi.c (ffff8000109a1f70)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_var_len_cdb_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
```
```
In drivers/ata/libata-zpodd.c (ffff8000109b6ba8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/net/tun.c (ffff8000109dd388)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7034)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a02de4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/slip/slhc.c (ffff800010a05228)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
```
```
In drivers/cdrom/cdrom.c (ffff800010a0eb28)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
```
In drivers/firmware/dmi_scan.c (ffff8000114a410c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/of/property.c (ffff800010b6e774)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u16_array
```
```
In net/core/skbuff.c (ffff800010bb6ca8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_dump
```
```
In net/core/flow_dissector.c (ffff800010bc4190)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffff800010bd27dc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_add_pack
```
```
In net/core/ethtool.c (ffff800010bd9364)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/neighbour.c (ffff800010be8a48)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/utils.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/core/filter.c (ffff800010bf86fc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/core/tso.c (ffff800010c04a60)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-procfs.c (ffff800010c0de3c)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/core/netpoll.c (ffff800010c11558)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffff800010c1962c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_kfree_skb
  - net/core/net-traces.c:trace_event_raw_event_kfree_skb
```
```
In net/core/drop_monitor.c (ffff800010c1c2ac)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/802/fc.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/802/fddi.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c3fff8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/netlink/af_netlink.c (ffff800010c4b698)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/route.c (ffff800010c585ec)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_input.c (ffff800010c5e114)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fbb4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffff800010c65528)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6cc30)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_input.c (ffff800010c7a650)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffff800010c82cf4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffff800010c89814)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a468)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8fbe0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93960)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/raw.c (ffff800010c97ca0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c991dc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffff800010ca02e4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffff800010ca2548)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffff800010ca4908)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffff800010caa3ac)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/igmp.c (ffff800010cae694)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ping.c (ffff800010cbfb8c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/fib_rules.c (ffff800010cc8754)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cccc38)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/syncookies.c (ffff800010cd21c8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6db4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7ac4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdba50)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffff800010ce39f4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9d2c)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb79c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffff800010cf66f0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/ip6_output.c (ffff800010cfb4a0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfd1b4)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0f9d4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ndisc.c (ffff800010d22628)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d237c8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffff800010d2a064)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffff800010d2c7b0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffff800010d2eed0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d35224)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d35fa8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffff800010d3a220)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
```
In net/ipv6/datagram.c (ffff800010d3da98)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d40768)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/ip6mr.c (ffff800010d45e14)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffff800010d48d7c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b4b0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/syncookies.c (ffff800010d4c728)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffff800010d4d290)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/exthdrs_core.c (ffff800010d53480)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/ip6_checksum.c (ffff800010d538e8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffff800010d54804)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffff800010d562e0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffff800010d567fc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffff800010d60544)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/ncsi/ncsi-cmd.c (ffff800010d74954)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_build_header
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d77038)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/ncsi/ncsi-aen.c (ffff800010d77c34)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7db24)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In lib/decompress_unlzo.c (ffff8000114b7c78)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/vsprintf.c (ffff800010d94afc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip6_compressed_string
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In fs/jbd2/commit.c (ffffffe000346382)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347bd6)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/nls/nls_base.c (ffffffe00036d430)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - fs/nls/nls_base.c:utf16s_to_utf8s
  - fs/nls/nls_base.c:utf16s_to_utf8s
  - fs/nls/nls_base.c:utf8s_to_utf16s
```
```
In security/keys/trusted.c (ffffffe000398930)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
```
```
In security/selinux/hooks.c (ffffffe0003a596a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/smack/smack_lsm.c (ffffffe0003c4c0c)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/lsm_audit.c (ffffffe0003c9afc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In security/tomoyo/network.c (ffffffe0003d4fc4)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/apparmor/match.c (ffffffe0003ddff0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/file.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/apparmor/net.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffe0003f54c2)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In block/partitions/aix.c (ffffffe00043bc06)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffe00043c634)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/sun.c (ffffffe000440278)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/sysv68.c (ffffffe000441cb6)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/t10-pi.c (ffffffe000451774)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In block/sed-opal.c (ffffffe0004599b2)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - block/sed-opal.c:opal_discovery0_end
  - block/sed-opal.c:opal_discovery0_end
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004adffe)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16be
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056eefe)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe00056fb06)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffe000593784)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_16_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_16_be
  - drivers/base/regmap/regmap.c:regmap_format_16_be
```
```
In drivers/base/regmap/regmap-i2c.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059c148)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
```
```
In drivers/scsi/sr.c (ffffffe0005f0a38)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
```
```
In drivers/net/tun.c (ffffffe00062859e)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062ec6c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/slip/slhc.c (ffffffe00062f9d6)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
```
```
In drivers/cdrom/cdrom.c (ffffffe0006325ac)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071ad84)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In drivers/of/property.c (ffffffe000722f40)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u16_array
```
```
In net/core/skbuff.c (ffffffe000746922)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_dump
```
```
In net/core/flow_dissector.c (ffffffe000750686)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffe00075cac4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:dev_add_pack
```
```
In net/core/ethtool.c (ffffffe000762746)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/neighbour.c (ffffffe00076ce74)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/utils.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/core/filter.c (ffffffe00077a3ea)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
```
```
In net/core/tso.c (ffffffe00078362a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/net-procfs.c (ffffffe00078aa2e)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/core/netpoll.c (ffffffe00078d6f8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffe000790e60)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_kfree_skb
  - net/core/net-traces.c:trace_event_raw_event_kfree_skb
```
```
In net/core/drop_monitor.c (ffffffe00079634e)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ethernet/eth.c (ffffffe0007a8172)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/802/fc.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/802/fddi.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/sched/cls_api.c (ffffffe0007afb6c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/netlink/af_netlink.c (ffffffe0007b8dbc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/ipv4/route.c (ffffffe0007c107e)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_input.c (ffffffe0007c6c72)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c797e)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffe0007ccd52)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d21e6)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_input.c (ffffffe0007de2d4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffe0007e44e2)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea6de)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb6fa)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efa42)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2fbe)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/raw.c (ffffffe0007f60d6)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f774e)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc9e6)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffe0007fe534)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/icmp.c (ffffffe00080074a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/af_inet.c (ffffffe000805208)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/igmp.c (ffffffe000809a26)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:add_grhead
```
```
In net/ipv4/ping.c (ffffffe00081590a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/fib_rules.c (ffffffe00081ca26)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081ed6a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/syncookies.c (ffffffe00082358a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008276b2)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffe000828142)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082d0ee)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffe000832b84)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/xfrm/xfrm_input.c (ffffffe000837cc8)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe000839122)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffe000841e2a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/ip6_output.c (ffffffe000845f6a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000847560)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffe000853508)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ndisc.c (ffffffe000864182)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000864f62)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffe00086a868)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffe00086cada)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffe00086ebe8)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe0008725fa)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008734fe)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffe000876ecc)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
```
In net/ipv6/datagram.c (ffffffe00087a15c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c06a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/ip6mr.c (ffffffe00087dcd2)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffe0008822ce)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffe0008844f4)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffe00088546c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffe0008860f6)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/exthdrs_core.c (ffffffe00088b190)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b5e0)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c16e)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/uapi/linux/swab.h:47
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088db76)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffe00088e1b4)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_run_all_ft_ops
```
```
In net/8021q/vlan_core.c (ffffffe000895948)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4a1a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_build_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a6e8a)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/ncsi/ncsi-aen.c (ffffffe0008a752c)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab2fa)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In lib/vsprintf.c (ffffffe0008bed50)
Location: include/uapi/linux/swab.h:47
Inline: True
Inline callers:
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip6_compressed_string
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
