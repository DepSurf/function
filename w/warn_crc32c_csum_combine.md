# Function: <code>warn_crc32c_csum_combine</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b85b0)
Location: net/core/skbuff.c:2263
Inline: True
```
**Symbols:**

```
ffffffff817b85b0-ffffffff817b85db: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830f80)
Location: net/core/skbuff.c:2638
Inline: True
```
**Symbols:**

```
ffffffff81830f80-ffffffff81830fab: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2654
Inline: True
```
**Symbols:**

```
ffffffff8187b450-ffffffff8187b46a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff8188342a-ffffffff81883442: warn_crc32c_csum_combine.cold.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818a3e71)
Location: net/core/skbuff.c:2709
Inline: True
```
**Symbols:**

```
ffffffff8189c290-ffffffff8189c2aa: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff818a3e71-ffffffff818a3e89: warn_crc32c_csum_combine.cold.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818eec96)
Location: net/core/skbuff.c:2875
Inline: True
```
**Symbols:**

```
ffffffff818e6b10-ffffffff818e6b2a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff818eec96-ffffffff818eecae: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81920c72)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
ffffffff81918c60-ffffffff81918c7a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff81920c72-ffffffff81920c8a: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819f49ef)
Location: net/core/skbuff.c:2876
Inline: True
```
**Symbols:**

```
ffffffff819ea480-ffffffff819ea49a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff819f49ef-ffffffff819f4a07: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81c30968)
Location: net/core/skbuff.c:2894
Inline: True
```
**Symbols:**

```
ffffffff819ea1b0-ffffffff819ea1ca: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff81c30968-ffffffff81c30980: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81c22c4b)
Location: net/core/skbuff.c:2977
Inline: True
```
**Symbols:**

```
ffffffff819d0770-ffffffff819d078a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff81c22c4b-ffffffff81c22c63: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81d350e7)
Location: net/core/skbuff.c:3049
Inline: True
```
**Symbols:**

```
ffffffff81a803b0-ffffffff81a803ca: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff81d350e7-ffffffff81d350ff: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81f011b0)
Location: net/core/skbuff.c:3098
Inline: True
```
**Symbols:**

```
ffffffff81bf49b0-ffffffff81bf49d2: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff81f011b0-ffffffff81f011c8: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2850)
Location: net/core/skbuff.c:3304
Inline: True
```
**Symbols:**

```
ffffffff81da2850-ffffffff81da288d: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e11280)
Location: net/core/skbuff.c:3474
Inline: True
```
**Symbols:**

```
ffffffff81e11280-ffffffff81e112bd: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecddb0)
Location: net/core/skbuff.c:3562
Inline: True
```
**Symbols:**

```
ffffffff81ecddb0-ffffffff81ecdded: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1d08)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
ffff800010bb1d08-ffff800010bb1d48: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf670)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
c0ccf670-c0ccf6b0: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c89470)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
c000000000c89470-c000000000c894cc: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744340)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
ffffffe000744340-ffffffe000744380: warn_crc32c_csum_combine (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818c0c72)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
ffffffff818b8c60-ffffffff818b8c7a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff818c0c72-ffffffff818c0c8a: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8187abb2)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
ffffffff81872bb0-ffffffff81872bca: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff8187abb2-ffffffff8187abca: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81911c72)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
ffffffff81909c60-ffffffff81909c7a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff81911c72-ffffffff81911c8a: warn_crc32c_csum_combine.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_combine(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81932dd2)
Location: net/core/skbuff.c:2877
Inline: True
```
**Symbols:**

```
ffffffff8192ad60-ffffffff8192ad7a: warn_crc32c_csum_combine (STB_LOCAL)
ffffffff81932dd2-ffffffff81932dea: warn_crc32c_csum_combine.cold (STB_LOCAL)
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
