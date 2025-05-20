# Function: <code>___siphash_aligned</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff817c3e5b)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/ipv6/syncookies.c (ffffffff818c7e89)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff8183d907)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/ipv6/syncookies.c (ffffffff8194b40d)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff81888123)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/ipv6/syncookies.c (ffffffff819a46bb)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff818a8cf3)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/ipv6/syncookies.c (ffffffff819db1cb)
Location: include/linux/siphash.h:51
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff818f4393)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8d70)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff81a49e4b)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff81a50ae4)
Location: include/linux/siphash.h:56
Inline: True
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
In net/core/secure_seq.c (ffffffff81926343)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff81928ab9)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df9d0)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff81a80a0b)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff81a87704)
Location: include/linux/siphash.h:56
Inline: True
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
In fs/crypto/fname.c (ffffffff81390706)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_siphash
```
```
In net/core/secure_seq.c (ffffffff819fa31f)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff819fa935)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accf95)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv6/syncookies.c (ffffffff81b7b68f)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/output_core.c (ffffffff81b82ca8)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
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
In fs/crypto/fname.c (ffffffff813a1b86)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_siphash
```
```
In net/core/secure_seq.c (ffffffff819f9f0f)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff819fa545)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8f99)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv6/syncookies.c (ffffffff81b8a6cf)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/output_core.c (ffffffff81b92328)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
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
In fs/crypto/fname.c (ffffffff813a8d26)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_siphash
```
```
In net/core/secure_seq.c (ffffffff819e00d3)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff819e0735)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4559)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/route.c (ffffffff81b3d820)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff81b79523)
Location: include/linux/siphash.h:56
Inline: True
```
</details>
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
In net/core/secure_seq.c (ffff800010bc2598)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffff800010bc4da8)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c932e8)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffff800010d4c240)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/output_core.c (ffff800010d53fec)
Location: include/linux/siphash.h:56
Inline: True
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
In net/core/secure_seq.c (c0cdd918)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (c0ce03c0)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (c0da1dd8)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (c0e4d488)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (c0e547a8)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
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
In net/core/secure_seq.c (c000000000c9c400)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (c000000000c9f5c4)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3860)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (c000000000e8281c)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/output_core.c (c000000000e8c9f8)
Location: include/linux/siphash.h:56
Inline: True
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
In net/core/secure_seq.c (ffffffe00074f536)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffe00075184c)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2a8e)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffe000884fe4)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffe00088bb10)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
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
In net/core/secure_seq.c (ffffffff818c6343)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff818c8ab9)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f840)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff81a2009b)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff81a26d94)
Location: include/linux/siphash.h:56
Inline: True
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
In net/core/secure_seq.c (ffffffff81880283)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff818829f9)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939300)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff819dce5b)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff819e3b54)
Location: include/linux/siphash.h:56
Inline: True
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
In net/core/secure_seq.c (ffffffff81917343)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff81919ab9)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199d1aa)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_id
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae234)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:nf_expect_get_id
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea010)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff81a8ab1b)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff81a92944)
Location: include/linux/siphash.h:56
Inline: True
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
In net/core/secure_seq.c (ffffffff81938553)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff8193acf9)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3e40)
Location: include/linux/siphash.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff81a9777b)
Location: include/linux/siphash.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff81a9ea44)
Location: include/linux/siphash.h:56
Inline: True
```
</details>
</li>
</ul>

## Differences
