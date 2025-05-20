# Function: <code>__tun_build_skb</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8175fd60)
Location: drivers/net/tun.c:1613
Inline: True
```
**Symbols:**

```
ffffffff8175fd60-ffffffff8175fdeb: __tun_build_skb.isra.56 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8179d470)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffffffff8179d470-ffffffff8179d510: __tun_build_skb.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817c0f10)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffffffff817c0f10-ffffffff817c0fb0: __tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188b1e0)
Location: drivers/net/tun.c:1569
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff8188b1e0-ffffffff8188b27c: __tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81899380)
Location: drivers/net/tun.c:1500
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff81899380-ffffffff8189941c: __tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187b760)
Location: drivers/net/tun.c:1511
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff8187b760-ffffffff8187b7f8: __tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190cc90)
Location: drivers/net/tun.c:1567
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff8190cc90-ffffffff8190cd28: __tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a628f0)
Location: drivers/net/tun.c:1595
Inline: False
```
**Symbols:**

```
ffffffff81a628f0-ffffffff81a629bf: __tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bee900)
Location: drivers/net/tun.c:1598
Inline: False
```
**Symbols:**

```
ffffffff81bee900-ffffffff81bee9cf: __tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c46e30)
Location: drivers/net/tun.c:1604
Inline: False
```
**Symbols:**

```
ffffffff81c46e30-ffffffff81c46eff: __tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfc750)
Location: drivers/net/tun.c:1607
Inline: False
```
**Symbols:**

```
ffffffff81cfc750-ffffffff81cfc81c: __tun_build_skb (STB_LOCAL)
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
In drivers/net/tun.c (ffff8000109db9c8)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffff8000109db9c8-ffff8000109dbabc: __tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__tun_build_skb(struct tun_file *tfile, struct page_frag *alloc_frag, char *buf, int buflen, int len, int pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac365c)
Location: drivers/net/tun.c:1604
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c0ac365c-c0ac3704: __tun_build_skb (STB_LOCAL)
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
In drivers/net/tun.c (c000000000a9def0)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
c000000000a9def0-c000000000a9e038: __tun_build_skb.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffe0006263ae)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffffffe0006263ae-ffffffe00062645c: __tun_build_skb.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817859e0)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffffffff817859e0-ffffffff81785a80: __tun_build_skb.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81765330)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffffffff81765330-ffffffff817653d0: __tun_build_skb.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817b5d90)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffffffff817b5d90-ffffffff817b5e30: __tun_build_skb.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817d0200)
Location: drivers/net/tun.c:1604
Inline: True
```
**Symbols:**

```
ffffffff817d0200-ffffffff817d02a0: __tun_build_skb.isra.0 (STB_LOCAL)
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
