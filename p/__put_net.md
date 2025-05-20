# Function: <code>__put_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8170fbd0)
Location: net/core/net_namespace.c:453
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:single_open_net
  - net/core/sock.c:sk_destruct
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff8170fbd0-ffffffff8170fc35: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81777500)
Location: net/core/net_namespace.c:453
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81777500-ffffffff81777565: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a4580)
Location: net/core/net_namespace.c:484
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff817a4580-ffffffff817a45e5: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c2720)
Location: net/core/net_namespace.c:523
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff817c2720-ffffffff817c2785: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183c060)
Location: net/core/net_namespace.c:524
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:single_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:get_target_net
```
**Symbols:**

```
ffffffff8183c060-ffffffff8183c0c5: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81886c00)
Location: net/core/net_namespace.c:591
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:get_target_net
```
**Symbols:**

```
ffffffff81886c00-ffffffff81886c3c: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a72f0)
Location: net/core/net_namespace.c:591
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_sk_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff818a72f0-ffffffff818a732c: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f2a40)
Location: net/core/net_namespace.c:635
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff818f2a40-ffffffff818f2a7c: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819249a0)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819249a0-ffffffff819249dc: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8d46)
Location: net/core/net_namespace.c:644
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_netns_get
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819f7fb0-ffffffff819f7fec: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f881c)
Location: net/core/net_namespace.c:645
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_netns_get
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819f7a10-ffffffff819f7a4c: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819df04c)
Location: net/core/net_namespace.c:636
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819ddb90-ffffffff819ddbcc: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8f42c)
Location: net/core/net_namespace.c:638
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a8de10-ffffffff81a8de4c: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c05296)
Location: net/core/net_namespace.c:637
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81c03a50-ffffffff81c03aa4: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db4b26)
Location: net/core/net_namespace.c:656
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81db30f0-ffffffff81db3144: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e251c6)
Location: net/core/net_namespace.c:657
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81e236c0-ffffffff81e23714: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee3126)
Location: net/core/net_namespace.c:661
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - net/core/sock.c:__sk_destruct
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
**Symbols:**

```
ffffffff81ee1620-ffffffff81ee1674: __put_net (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc0440)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffff800010bc0440-ffff800010bc04a8: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdbec4)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
c0cdbec4-c0cdbf10: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c99c60)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
c000000000c99c60-c000000000c99cdc: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074df7a)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffe00074df7a-ffffffe00074dfd6: __put_net (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c49a0)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff818c49a0-ffffffff818c49dc: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187e8e0)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8187e8e0-ffffffff8187e91c: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819159a0)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/netfilter/nfnetlink_log.c:nfulnl_instance_free_rcu
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819159a0-ffffffff819159dc: __put_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __put_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81936b90)
Location: net/core/net_namespace.c:638
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
  - fs/fs_context.c:put_fs_context
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/sock.c:__sk_destruct
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81936b90-ffffffff81936bcc: __put_net (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
