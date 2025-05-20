# Function: <code>skb_dump</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff818eed27-ffffffff818ef14a: skb_dump.cold (STB_LOCAL)
ffffffff818e73a0-ffffffff818e740b: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81920d03-ffffffff8192119d: skb_dump.cold (STB_LOCAL)
ffffffff819197a0-ffffffff81919805: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:717
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff819f452a-ffffffff819f4991: skb_dump.cold (STB_LOCAL)
ffffffff819ea010-ffffffff819ea080: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81c304c3)
Location: net/core/skbuff.c:731
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81c304c3-ffffffff81c3090a: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81c2279c)
Location: net/core/skbuff.c:779
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81c2279c-ffffffff81c22be6: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81d34c24)
Location: net/core/skbuff.c:795
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:netdev_rx_csum_fault
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81d34c24-ffffffff81d3506e: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81f011e0)
Location: net/core/skbuff.c:800
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:netdev_rx_csum_fault
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81f011e0-ffffffff81f01674: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3110)
Location: net/core/skbuff.c:978
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:netdev_rx_csum_fault
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81da3110-ffffffff81da3662: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e11ce0)
Location: net/core/skbuff.c:1118
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81e11ce0-ffffffff81e12254: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eceea0)
Location: net/core/skbuff.c:1204
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81eceea0-ffffffff81ecf41b: skb_dump (STB_GLOBAL)
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
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb42f8)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffff800010bb42f8-ffff800010bb4740: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccffec)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
c0ccffec-c0cd04cc: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c874c0)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
c000000000c874c0-c000000000c87a24: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007420c2)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffe0007420c2-ffffffe0007424bc: skb_dump (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff818c0d03-ffffffff818c119d: skb_dump.cold (STB_LOCAL)
ffffffff818b97a0-ffffffff818b9805: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff8187ac43-ffffffff8187b0dd: skb_dump.cold (STB_LOCAL)
ffffffff818736f0-ffffffff81873755: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81911d03-ffffffff8191219d: skb_dump.cold (STB_LOCAL)
ffffffff8190a7a0-ffffffff8190a805: skb_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void skb_dump(const char *level, const struct sk_buff *skb, bool full_pkt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:718
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_dump
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff81932e63-ffffffff8193333a: skb_dump.cold (STB_LOCAL)
ffffffff8192b8a0-ffffffff8192b905: skb_dump (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
