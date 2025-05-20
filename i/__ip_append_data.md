# Function: <code>__ip_append_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175d310)
Location: net/ipv4/ip_output.c:865
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff8175d310-ffffffff8175ddc6: __ip_append_data.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817c87c0)
Location: net/ipv4/ip_output.c:863
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff817c87c0-ffffffff817c9260: __ip_append_data.isra.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817f8330)
Location: net/ipv4/ip_output.c:904
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff817f8330-ffffffff817f8df8: __ip_append_data.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81818760)
Location: net/ipv4/ip_output.c:911
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81818760-ffffffff81819223: __ip_append_data.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818989d0)
Location: net/ipv4/ip_output.c:856
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff818989d0-ffffffff81899269: __ip_append_data.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818eca70)
Location: net/ipv4/ip_output.c:858
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff818eca70-ffffffff818ed438: __ip_append_data.isra.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191a280)
Location: net/ipv4/ip_output.c:860
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff8191a280-ffffffff8191ae7a: __ip_append_data.isra.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:949
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff8197c470-ffffffff8197d126: __ip_append_data.isra.0 (STB_LOCAL)
ffffffff8197eb3a-ffffffff8197eb4d: __ip_append_data.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b2e10)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff819b2e10-ffffffff819b3acd: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9ce00)
Location: net/ipv4/ip_output.c:952
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81a9ce00-ffffffff81a9dbc6: __ip_append_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa6cc0)
Location: net/ipv4/ip_output.c:959
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81aa6cc0-ffffffff81aa7a96: __ip_append_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a91e40)
Location: net/ipv4/ip_output.c:960
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81a91e40-ffffffff81a92c85: __ip_append_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4d250)
Location: net/ipv4/ip_output.c:959
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81b4d250-ffffffff81b4e087: __ip_append_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdaa30)
Location: net/ipv4/ip_output.c:959
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81cdaa30-ffffffff81cdb92f: __ip_append_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:959
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81e9b250-ffffffff81e9c2bf: __ip_append_data (STB_LOCAL)
ffffffff820ae406-ffffffff820ae465: __ip_append_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:950
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81ef9c70-ffffffff81efae94: __ip_append_data (STB_LOCAL)
ffffffff8212f91f-ffffffff8212f97e: __ip_append_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:951
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81fbdba0-ffffffff81fbed9a: __ip_append_data (STB_LOCAL)
ffffffff822116a9-ffffffff82211711: __ip_append_data.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c62838)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffff800010c62838-ffff800010c63424: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ip_append_data(struct sock *sk, struct flowi4 *fl4, struct sk_buff_head *queue, struct inet_cork *cork, struct page_frag *pfrag, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d731cc)
Location: net/ipv4/ip_output.c:953
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
c0d731cc-c0d73e30: __ip_append_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d67380)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
c000000000d67380-c000000000d68230: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007cb286)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffe0007cb286-ffffffe0007cbca0: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81952c80)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff81952c80-ffffffff8195393d: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190c770)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff8190c770-ffffffff8190d42d: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bd450)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff819bd450-ffffffff819be10d: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c6d60)
Location: net/ipv4/ip_output.c:953
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
**Symbols:**

```
ffffffff819c6d60-ffffffff819c7a1d: __ip_append_data.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
