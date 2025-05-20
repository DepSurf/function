# Function: <code>__do_once_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81400d80)
Location: lib/once.c:36
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
ffffffff81400d80-ffffffff81400dbf: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81448520)
Location: lib/once.c:36
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
ffffffff81448520-ffffffff8144855f: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81466f10)
Location: lib/once.c:36
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
ffffffff81466f10-ffffffff81466f4f: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8146c3d0)
Location: lib/once.c:36
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
ffffffff8146c3d0-ffffffff8146c40f: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff814986d0)
Location: lib/once.c:37
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
ffffffff814986d0-ffffffff8149870f: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff814cd8b0)
Location: lib/once.c:37
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
ffffffff814cd8b0-ffffffff814cd8f6: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff814e1f80)
Location: lib/once.c:37
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
ffffffff814e1f80-ffffffff814e1fc6: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8150de30)
Location: lib/once.c:37
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
ffffffff8150de30-ffffffff8150de72: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8152bc80)
Location: lib/once.c:37
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
ffffffff8152bc80-ffffffff8152bcc2: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8158f660)
Location: lib/once.c:37
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
ffffffff8158f660-ffffffff8158f6a2: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff815ac190)
Location: lib/once.c:37
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
ffffffff815ac190-ffffffff815ac1d2: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff815b6e30)
Location: lib/once.c:42
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
ffffffff815b6e30-ffffffff815b6e72: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/once.c (ffffffff8161d44b)
Location: lib/once.c:42
Inline: True
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
ffffffff81cdad41-ffffffff81cdad56: __do_once_start.cold (STB_LOCAL)
ffffffff8161d410-ffffffff8161d461: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/once.c (ffffffff816eaf23)
Location: lib/once.c:42
Inline: True
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
ffffffff81e935fd-ffffffff81e93612: __do_once_start.cold (STB_LOCAL)
ffffffff816eaee0-ffffffff816eaf41: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/once.c (ffffffff817db4d3)
Location: lib/once.c:42
Inline: True
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
ffffffff820787c5-ffffffff820787da: __do_once_start.cold (STB_LOCAL)
ffffffff817db490-ffffffff817db4f1: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/once.c (ffffffff8181a743)
Location: lib/once.c:42
Inline: True
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
ffffffff820f8d70-ffffffff820f8d85: __do_once_start.cold (STB_LOCAL)
ffffffff8181a700-ffffffff8181a761: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/once.c (ffffffff8185fa93)
Location: lib/once.c:42
Inline: True
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
ffffffff821d6891-ffffffff821d68a6: __do_once_start.cold (STB_LOCAL)
ffffffff8185fa50-ffffffff8185fab1: __do_once_start (STB_GLOBAL)
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
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffff8000106375f8)
Location: lib/once.c:37
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
ffff8000106375f8-ffff8000106376cc: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (c07dd274)
Location: lib/once.c:37
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
c07dd274-c07dd2c4: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (c0000000007dd5c0)
Location: lib/once.c:37
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
c0000000007dd5c0-c0000000007dd660: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffe000464888)
Location: lib/once.c:37
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
ffffffe000464888-ffffffe0004648e0: __do_once_start (STB_GLOBAL)
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
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81524260)
Location: lib/once.c:37
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
ffffffff81524260-ffffffff815242a2: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81514540)
Location: lib/once.c:37
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
ffffffff81514540-ffffffff81514582: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff815202f0)
Location: lib/once.c:37
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
ffffffff815202f0-ffffffff81520332: __do_once_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __do_once_start(bool *done, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff81539c70)
Location: lib/once.c:37
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
ffffffff81539c70-ffffffff81539cb2: __do_once_start (STB_GLOBAL)
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
