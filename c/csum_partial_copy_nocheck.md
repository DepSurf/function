# Function: <code>csum_partial_copy_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817af0)
Location: arch/x86/lib/csum-wrappers_64.c:130
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81817af0-ffffffff81817b06: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818915a0)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff818915a0-ffffffff818915b6: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818c5eb0)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff818c5eb0-ffffffff818c5ec6: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818fba80)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff818fba80-ffffffff818fba96: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819828d0)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff819828d0-ffffffff819828e6: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819dee00)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff819dee00-ffffffff819dee16: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a19d30)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81a19d30-ffffffff81a19d46: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a89a50)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81a89a50-ffffffff81a89a66: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ac0cf0)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81ac0cf0-ffffffff81ac0d06: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd140)
Location: arch/x86/lib/csum-wrappers_64.c:132
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff815fd140-ffffffff815fd156: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621f40)
Location: arch/x86/lib/csum-wrappers_64.c:72
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81621f40-ffffffff81621f50: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81605850)
Location: arch/x86/lib/csum-wrappers_64.c:72
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81605850-ffffffff81605860: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81674140)
Location: arch/x86/lib/csum-wrappers_64.c:72
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81674140-ffffffff81674150: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e7e0)
Location: arch/x86/lib/csum-wrappers_64.c:70
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff8178e7e0-ffffffff8178e7fa: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c0e0)
Location: arch/x86/lib/csum-wrappers_64.c:70
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff8204c0e0-ffffffff8204c0fa: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820ca9d0)
Location: arch/x86/lib/csum-wrappers_64.c:70
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff820ca9d0-ffffffff820ca9ea: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5210)
Location: arch/x86/lib/csum-wrappers_64.c:65
Inline: False
Direct callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff821a5210-ffffffff821a522a: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
c0e7ca80-c0e7cdec: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a5fb40)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81a5fb40-ffffffff81a5fb56: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a1cc10)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81a1cc10-ffffffff81a1cc26: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81acbf30)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81acbf30-ffffffff81acbf46: csum_partial_copy_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__wsum csum_partial_copy_nocheck(const void *src, void *dst, int len, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ad8480)
Location: arch/x86/lib/csum-wrappers_64.c:131
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/raw.c:raw_getfrag
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv6/raw.c:raw6_getfrag
```
**Symbols:**

```
ffffffff81ad8480-ffffffff81ad8496: csum_partial_copy_nocheck (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
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
