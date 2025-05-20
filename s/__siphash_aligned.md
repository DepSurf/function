# Function: <code>__siphash_aligned</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff818f51e0)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff818f51e0-ffffffff818f5434: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff8197bbe0)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff8197bbe0-ffffffff8197be34: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff819d8150)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff819d8150-ffffffff819d838f: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a10370)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81a10370-ffffffff81a105af: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a7f900)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81a7f900-ffffffff81a7fb36: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81ab6b00)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81ab6b00-ffffffff81ab6d36: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff815f1740)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_siphash
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:__flow_hash_from_keys
```
**Symbols:**

```
ffffffff815f1740-ffffffff815f196b: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81615df0)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_siphash
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:__flow_hash_from_keys
```
**Symbols:**

```
ffffffff81615df0-ffffffff8161601b: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff815f9470)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_siphash
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:__flow_hash_from_keys
```
**Symbols:**

```
ffffffff815f9470-ffffffff815f9691: __siphash_aligned (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffff800010d912f0)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
**Symbols:**

```
ffff800010d912f0-ffff800010d914dc: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (c0e8be6c)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
c0e8be6c-c0e8c460: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (c000000000ed4830)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
**Symbols:**

```
c000000000ed4830-c000000000ed4ad8: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffe0008ba148)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffe0008ba148-ffffffe0008ba474: __siphash_aligned (STB_GLOBAL)
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
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a55950)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81a55950-ffffffff81a55b86: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a12a30)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81a12a30-ffffffff81a12c66: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81ac1d40)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_id
  - net/netfilter/nf_conntrack_netlink.c:nf_expect_get_id
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81ac1d40-ffffffff81ac1f76: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 __siphash_aligned(const void *data, size_t len, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81ace210)
Location: lib/siphash.c:52
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/ipv6/syncookies.c:cookie_hash
```
**Symbols:**

```
ffffffff81ace210-ffffffff81ace446: __siphash_aligned (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
