# Function: <code>csum_partial_ext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705530)
Location: include/net/checksum.h:116
Inline: False
```
**Symbols:**

```
ffffffff81705530-ffffffff8170553b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c1a0)
Location: include/net/checksum.h:116
Inline: False
```
**Symbols:**

```
ffffffff8176c1a0-ffffffff8176c1ab: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799380)
Location: include/net/checksum.h:116
Inline: False
```
**Symbols:**

```
ffffffff81799380-ffffffff8179938b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b8000)
Location: include/net/checksum.h:116
Inline: False
```
**Symbols:**

```
ffffffff817b8000-ffffffff817b800b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830a40)
Location: include/net/checksum.h:116
Inline: False
```
**Symbols:**

```
ffffffff81830a40-ffffffff81830a4b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187af10)
Location: include/net/checksum.h:116
Inline: False
```
**Symbols:**

```
ffffffff8187af10-ffffffff8187af1b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b8b0)
Location: include/net/checksum.h:116
Inline: False
```
**Symbols:**

```
ffffffff8189b8b0-ffffffff8189b8bb: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5f7e)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff818e5e00-ffffffff818e5e0b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819180cc)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81917f60-ffffffff81917f6b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb23c)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff819ea470-ffffffff819ea47b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eaf5c)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff819ea1a0-ffffffff819ea1ab: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1489)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff819d0760-ffffffff819d076b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80f49)
Location: include/net/checksum.h:115
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81a7f340-ffffffff81a7f34b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf59ee)
Location: include/net/checksum.h:117
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81bf3610-ffffffff81bf3625: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3c1e)
Location: include/net/checksum.h:117
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81da1350-ffffffff81da1365: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1287f)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81e0fc20-ffffffff81e0fc35: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecfa3f)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81ecc6d0-ffffffff81ecc6e5: csum_partial_ext (STB_LOCAL)
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
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb15b0)
Location: include/net/checksum.h:112
Inline: False
```
**Symbols:**

```
ffff800010bb15b0-ffff800010bb15c4: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf040)
Location: include/net/checksum.h:112
Inline: False
```
**Symbols:**

```
c0ccf040-c0ccf054: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8bc40)
Location: include/net/checksum.h:112
Inline: False
```
**Symbols:**

```
c000000000c8bc40-c000000000c8bc6c: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000742f5c)
Location: include/net/checksum.h:112
Inline: False
```
**Symbols:**

```
ffffffe000742f5c-ffffffe000742f76: csum_partial_ext (STB_LOCAL)
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
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b80cc)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff818b7f60-ffffffff818b7f6b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187201c)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81871eb0-ffffffff81871ebb: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819090cc)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81908f60-ffffffff81908f6b: csum_partial_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_partial_ext(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192a187)
Location: include/net/checksum.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff8192a010-ffffffff8192a01b: csum_partial_ext (STB_LOCAL)
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
