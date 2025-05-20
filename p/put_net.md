# Function: <code>put_net</code>

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
In kernel/nsproxy.c (ffffffff810a1178)
Location: include/net/net_namespace.h:200
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff81120b66)
Location: include/net/net_namespace.h:200
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
```
```
In fs/proc/proc_net.c (ffffffff81286535)
Location: include/net/net_namespace.h:200
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:single_open_net
```
```
In net/core/sock.c (ffffffff817039a9)
Location: include/net/net_namespace.h:200
Inline: True
Inline callers:
  - net/core/sock.c:sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81710131)
Location: include/net/net_namespace.h:200
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/rtnetlink.c (ffffffff8172bafa)
Location: include/net/net_namespace.h:200
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a489d)
Location: include/net/net_namespace.h:203
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff81128ab8)
Location: include/net/net_namespace.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
```
```
In fs/proc/proc_net.c (ffffffff812b387b)
Location: include/net/net_namespace.h:203
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81654c84)
Location: include/net/net_namespace.h:203
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff8176886f)
Location: include/net/net_namespace.h:203
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81777d74)
Location: include/net/net_namespace.h:203
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81799e0e)
Location: include/net/net_namespace.h:203
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810aa4fd)
Location: include/net/net_namespace.h:204
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff81132712)
Location: include/net/net_namespace.h:204
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
```
```
In fs/proc/proc_net.c (ffffffff812c910b)
Location: include/net/net_namespace.h:204
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81682974)
Location: include/net/net_namespace.h:204
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff81796ca0)
Location: include/net/net_namespace.h:204
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff817a4d57)
Location: include/net/net_namespace.h:204
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff817c7bae)
Location: include/net/net_namespace.h:204
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a7067)
Location: include/net/net_namespace.h:212
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff811367df)
Location: include/net/net_namespace.h:212
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/proc/proc_net.c (ffffffff812d641b)
Location: include/net/net_namespace.h:212
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81697d84)
Location: include/net/net_namespace.h:212
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff817b508b)
Location: include/net/net_namespace.h:212
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff817c2f74)
Location: include/net/net_namespace.h:212
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff817e6482)
Location: include/net/net_namespace.h:212
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ad7f8)
Location: include/net/net_namespace.h:214
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff8114316b)
Location: include/net/net_namespace.h:214
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/proc/proc_net.c (ffffffff812fac6b)
Location: include/net/net_namespace.h:214
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81702c74)
Location: include/net/net_namespace.h:214
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff8182d4c7)
Location: include/net/net_namespace.h:214
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff8183cac4)
Location: include/net/net_namespace.h:214
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff818601e0)
Location: include/net/net_namespace.h:214
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:get_target_net
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b4553)
Location: include/net/net_namespace.h:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff81151ad9)
Location: include/net/net_namespace.h:233
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/proc/proc_net.c (ffffffff813281cb)
Location: include/net/net_namespace.h:233
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81741844)
Location: include/net/net_namespace.h:233
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff81875e76)
Location: include/net/net_namespace.h:233
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81887104)
Location: include/net/net_namespace.h:233
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff818ac2e2)
Location: include/net/net_namespace.h:233
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:get_target_net
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810bd6a3)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff8115e78f)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/proc/proc_net.c (ffffffff8133f3ab)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81765954)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff81897c56)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff818a7814)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff818d0367)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff818d8dc6)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_sk_lookup
```
```
In net/ipv4/devinet.c (ffffffff819566b9)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff819a26b7)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c36f9)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff8116adaa)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffffffff8130a517)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813676cc)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3985)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff818e2190)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff818f2d04)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffff818f4f83)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffffffff8191d1d4)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81926dc3)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffff819bb112)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a0ed34)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810cc809)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff81176c55)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffffffff8131d4e7)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff8137f94c)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c73d5)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff81914353)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81924c64)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffff81926e53)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffffffff8194f7ff)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81959483)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffff819f180f)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a45a77)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d5de7)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff811866e7)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8118c086)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff8122ad14)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff81357557)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813c9c90)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81891cfa)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff819e6360)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff819f8d06)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81a20fd9)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81a2e303)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/core/devlink.c (ffffffff81a5db63)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_netns_get
```
```
In net/ipv4/devinet.c (ffffffff81adf8cb)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b3c83d)
Location: include/net/net_namespace.h:264
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d09d5)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff8118389e)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8118929c)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff81232bbb)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff81363f07)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813db903)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a003a)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff819e5b70)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff819f87d6)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81a21a39)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81a2f863)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/core/devlink.c (ffffffff81a6756b)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_netns_get
```
```
In net/ipv4/devinet.c (ffffffff81aec854)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b4b54d)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d25b5)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff8118490e)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8118a10b)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff81236d60)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff8136a987)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813e2828)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882b4a)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff819cbc80)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff819df006)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81a08d28)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81a16944)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/core/devlink.c (ffffffff81a4ac4c)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/ipv4/devinet.c (ffffffff81ad7ea8)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b390af)
Location: include/net/net_namespace.h:259
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810e56f5)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff811acd7e)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff811b2b7c)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff81271340)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff813b9647)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff81434338)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819144ea)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff81a7b2e0)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81a8f3e6)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81abab48)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81ac7f44)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/core/devlink.c (ffffffff81b02d83)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/ipv4/devinet.c (ffffffff81b969a5)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81bff84f)
Location: include/net/net_namespace.h:261
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ff4fd)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff811de99b)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff811e4ef4)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff812c0438)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff8143f0a1)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff814ae40a)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69ad9)
Location: include/net/net_namespace.h:265
Inline: True
```
```
In net/core/sock.c (ffffffff81bef297)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81c05246)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81c3534f)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81c456b9)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/core/devlink.c (ffffffff81c866ec)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/ipv4/devinet.c (ffffffff81d28639)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81d99333)
Location: include/net/net_namespace.h:265
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8112421d)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff8122455b)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8122af14)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff81323c69)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff814cdd21)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff81544a1a)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc669)
Location: include/net/net_namespace.h:275
Inline: True
```
```
In net/core/sock.c (ffffffff81d9bae7)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81db4ad6)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81de888f)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81df9829)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/core/devlink.c (ffffffff81e40809)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/ipv4/devinet.c (ffffffff81ef0069)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81f68053)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8113151d)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff8123ab2b)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8124150e)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff81353e97)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff81503f11)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff8157c60d)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61ce9)
Location: include/net/net_namespace.h:275
Inline: True
```
```
In net/core/sock.c (ffffffff81e09cc4)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81e25176)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81e5a10a)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81e6b1a2)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffff81f4fab9)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81fc809e)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
```
In net/devlink/dev.c (ffffffff82044c6b)
Location: include/net/net_namespace.h:275
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8113c2ad)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/audit.c (ffffffff8125481b)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8125b342)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/net_namespace.c (ffffffff8137b3b6)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In fs/fs_context.c (ffffffff81538bd1)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff815b4f1d)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/netkit.c (ffffffff81ce5cad)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d186d9)
Location: include/net/net_namespace.h:277
Inline: True
```
```
In net/core/sock.c (ffffffff81ec66b6)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81ee30d6)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/rtnetlink.c (ffffffff81f194b7)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81f2a132)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffff82015c31)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/xfrm/xfrm_state_bpf.c (ffffffff82075ea8)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state
```
```
In net/ipv6/addrconf.c (ffffffff820957ac)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
```
In net/devlink/dev.c (ffffffff8210452b)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
</details>
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
In kernel/nsproxy.c (ffff80001012b550)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffff8000101ebc08)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffff8000103d58c4)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffff80001044d20c)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe7e4)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffff800010baca74)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffff800010bc0708)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffff800010bc33d0)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffff800010bf1518)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffff800010bfa958)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffff800010ca7ef8)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffff800010d0841c)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c037bb00)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (c042b828)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (c05aefec)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (c0611868)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (c0adc1cc)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (c0ccaa90)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (c0cdc36c)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (c0cde5a0)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (c0d09cb0)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (c0d14450)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (c0db4218)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (c0e0ebd4)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c000000000174014)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (c00000000025d250)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (c0000000004d80ec)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (c0000000005649fc)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6548)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (c000000000c80754)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (c000000000c9a090)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (c000000000c9d380)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (c000000000cd5f50)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (c000000000ce2d90)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (c000000000dbc4e4)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (c000000000e32864)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffe0000e0378)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffe000160354)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffffffe00028f3b0)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffe0002e1efa)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062bee0)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffe00073e98c)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffe00074e182)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffe00074fe7e)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffffffe0007732fa)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffe00077c63e)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffe000802eac)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffe0008504f0)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c6b89)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff8116f275)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffffffff81315ac7)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff81377f2c)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178beb5)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff818b4353)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff818c4c64)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffff818c6e53)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffffffff818ef7cf)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff818f9453)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffff819915af)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff819e5107)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b53a9)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff81162415)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffffffff813066b7)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813689fc)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81774c85)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff8186e2a3)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff8187eba4)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffff81880d93)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffffffff818a960f)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff818b3283)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffff8194b06f)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff819a1ec7)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c60d9)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff8116d045)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffffffff813138b7)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813759fc)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc255)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff81905353)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81915c64)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffff81917e53)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffffffff819407ff)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff8194a483)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b4a3)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_instance_free_rcu
```
```
In net/ipv4/devinet.c (ffffffff819fbe4f)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a4fb87)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ce529)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/audit.c (ffffffff8117a838)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In fs/fs_context.c (ffffffff81325107)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813894ac)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d65f5)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In net/core/sock.c (ffffffff81926443)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/net_namespace.c (ffffffff81936e64)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffff81939074)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/rtnetlink.c (ffffffff8196210f)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff8196bd93)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/devinet.c (ffffffff81a061c2)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a5bb67)
Location: include/net/net_namespace.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
</ul>

## Differences
