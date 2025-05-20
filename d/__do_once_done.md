# Function: <code>__do_once_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81400dc0)
Location: lib/once.c:54
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_get_hash
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/route.c:find_exception
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81400dc0-ffffffff81400e31: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81448560)
Location: lib/once.c:54
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81448560-ffffffff814485d1: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81466f50)
Location: lib/once.c:54
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81466f50-ffffffff81466fc1: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8146c410)
Location: lib/once.c:54
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff8146c410-ffffffff8146c481: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81498710)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81498710-ffffffff81498781: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff814cd900)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff814cd900-ffffffff814cd971: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff814e1fd0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff814e1fd0-ffffffff814e2041: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8150de80)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff8150de80-ffffffff8150def1: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8152bcd0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff8152bcd0-ffffffff8152bd41: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8158f6e0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff8158f6e0-ffffffff8158f754: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff815ac210)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff815ac210-ffffffff815ac284: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff815b6ec0)
Location: lib/once.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff815b6ec0-ffffffff815b6f52: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8161d470)
Location: lib/once.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff8161d470-ffffffff8161d502: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff816eaf50)
Location: lib/once.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff816eaf50-ffffffff816eafe9: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff817db5b0)
Location: lib/once.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff817db5b0-ffffffff817db5eb: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8181a820)
Location: lib/once.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff8181a820-ffffffff8181a85b: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8185fba0)
Location: lib/once.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff8185fba0-ffffffff8185fbdb: __do_once_done (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffff8000106376d0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffff8000106376d0-ffff80001063775c: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (c07dd2c4)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
c07dd2c4-c07dd34c: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (c0000000007dd6d0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
c0000000007dd6d0-c0000000007dd78c: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffe0004648e0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffe0004648e0-ffffffe00046495a: __do_once_done (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff815242b0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - drivers/nvme/host/pci.c:nvme_map_data
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff815242b0-ffffffff81524321: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81514590)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - drivers/nvme/host/pci.c:nvme_map_data
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81514590-ffffffff81514601: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81520340)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_id
  - net/netfilter/nf_conntrack_core.c:hash_conntrack_raw
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_dst_hash
  - net/netfilter/nf_conntrack_netlink.c:nf_expect_get_id
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81520340-ffffffff815203b1: __do_once_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __do_once_done(bool *done, struct static_key_true *once_key, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81539cc0)
Location: lib/once.c:55
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81539cc0-ffffffff81539d31: __do_once_done (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct static_key *once_key</code> ➡️ <code>struct static_key_true *once_key</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct module *mod</code>
</li>
</ul>
</details>
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
