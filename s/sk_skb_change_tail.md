# Function: <code>sk_skb_change_tail</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5790)
Location: net/core/filter.c:2968
Inline: False
```
**Symbols:**

```
ffffffff818b5790-ffffffff818b596e: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dc390)
Location: net/core/filter.c:3156
Inline: False
```
**Symbols:**

```
ffffffff818dc390-ffffffff818dc5fb: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3291
Inline: False
```
**Symbols:**

```
ffffffff8192d9dd-ffffffff8192da11: sk_skb_change_tail.cold (STB_LOCAL)
ffffffff81929490-ffffffff819296fc: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195bb70)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
ffffffff8195bb70-ffffffff8195bd57: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ed60)
Location: net/core/filter.c:3335
Inline: False
```
**Symbols:**

```
ffffffff81a2ed60-ffffffff81a2ef46: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30890)
Location: net/core/filter.c:3742
Inline: False
```
**Symbols:**

```
ffffffff81a30890-ffffffff81a30a2f: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19300)
Location: net/core/filter.c:3743
Inline: False
```
**Symbols:**

```
ffffffff81a19300-ffffffff81a19312: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac7560)
Location: net/core/filter.c:3712
Inline: False
```
**Symbols:**

```
ffffffff81ac7560-ffffffff81ac7572: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c43de0)
Location: net/core/filter.c:3713
Inline: False
```
**Symbols:**

```
ffffffff81c43de0-ffffffff81c43dfc: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df7fe0)
Location: net/core/filter.c:3723
Inline: False
```
**Symbols:**

```
ffffffff81df7fe0-ffffffff81df7ffc: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e676d0)
Location: net/core/filter.c:3768
Inline: False
```
**Symbols:**

```
ffffffff81e676d0-ffffffff81e676ec: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f26890)
Location: net/core/filter.c:3802
Inline: False
```
**Symbols:**

```
ffffffff81f26890-ffffffff81f268ac: sk_skb_change_tail (STB_GLOBAL)
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
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfcf18)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
ffff800010bfcf18-ffff800010bfd1ac: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1757c)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
c0d1757c-c0d177fc: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce5360)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
c000000000ce5360-c000000000ce56d8: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f9f0)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
ffffffe00077f9f0-ffffffe00077fbb6: sk_skb_change_tail (STB_GLOBAL)
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
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fbb40)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
ffffffff818fbb40-ffffffff818fbd27: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5970)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
ffffffff818b5970-ffffffff818b5b57: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194cb70)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
ffffffff8194cb70-ffffffff8194cd57: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 sk_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196e530)
Location: net/core/filter.c:3293
Inline: False
```
**Symbols:**

```
ffffffff8196e530-ffffffff8196e717: sk_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
