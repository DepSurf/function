# Function: <code>warn_crc32c_csum_update</code>

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
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b85e0)
Location: net/core/skbuff.c:2255
Inline: True
```
**Symbols:**

```
ffffffff817b85e0-ffffffff817b860b: warn_crc32c_csum_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830fb0)
Location: net/core/skbuff.c:2630
Inline: True
```
**Symbols:**

```
ffffffff81830fb0-ffffffff81830fdb: warn_crc32c_csum_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:2646
Inline: True
```
**Symbols:**

```
ffffffff8187b470-ffffffff8187b48a: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81883442-ffffffff8188345a: warn_crc32c_csum_update.cold.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818a3e89)
Location: net/core/skbuff.c:2701
Inline: True
```
**Symbols:**

```
ffffffff8189c2b0-ffffffff8189c2ca: warn_crc32c_csum_update (STB_LOCAL)
ffffffff818a3e89-ffffffff818a3ea1: warn_crc32c_csum_update.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818eecae)
Location: net/core/skbuff.c:2867
Inline: True
```
**Symbols:**

```
ffffffff818e6b30-ffffffff818e6b4a: warn_crc32c_csum_update (STB_LOCAL)
ffffffff818eecae-ffffffff818eecc6: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81920c8a)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
ffffffff81918c80-ffffffff81918c9a: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81920c8a-ffffffff81920ca2: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819f4a07)
Location: net/core/skbuff.c:2868
Inline: True
```
**Symbols:**

```
ffffffff819ea4a0-ffffffff819ea4ba: warn_crc32c_csum_update (STB_LOCAL)
ffffffff819f4a07-ffffffff819f4a1f: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81c30980)
Location: net/core/skbuff.c:2886
Inline: True
```
**Symbols:**

```
ffffffff819ea1d0-ffffffff819ea1ea: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81c30980-ffffffff81c30998: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81c22c63)
Location: net/core/skbuff.c:2969
Inline: True
```
**Symbols:**

```
ffffffff819d0790-ffffffff819d07aa: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81c22c63-ffffffff81c22c7b: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81d350ff)
Location: net/core/skbuff.c:3041
Inline: True
```
**Symbols:**

```
ffffffff81a803d0-ffffffff81a803ea: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81d350ff-ffffffff81d35117: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81f011c8)
Location: net/core/skbuff.c:3090
Inline: True
```
**Symbols:**

```
ffffffff81bf49e0-ffffffff81bf4a02: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81f011c8-ffffffff81f011e0: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da28a0)
Location: net/core/skbuff.c:3296
Inline: True
```
**Symbols:**

```
ffffffff81da28a0-ffffffff81da28dd: warn_crc32c_csum_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e112d0)
Location: net/core/skbuff.c:3466
Inline: True
```
**Symbols:**

```
ffffffff81e112d0-ffffffff81e1130d: warn_crc32c_csum_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecde00)
Location: net/core/skbuff.c:3554
Inline: True
```
**Symbols:**

```
ffffffff81ecde00-ffffffff81ecde3d: warn_crc32c_csum_update (STB_LOCAL)
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
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1d48)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
ffff800010bb1d48-ffff800010bb1d88: warn_crc32c_csum_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf6b0)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
c0ccf6b0-c0ccf6f0: warn_crc32c_csum_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c894d0)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
c000000000c894d0-c000000000c8952c: warn_crc32c_csum_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744380)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
ffffffe000744380-ffffffe0007443c0: warn_crc32c_csum_update (STB_LOCAL)
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
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818c0c8a)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
ffffffff818b8c80-ffffffff818b8c9a: warn_crc32c_csum_update (STB_LOCAL)
ffffffff818c0c8a-ffffffff818c0ca2: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8187abca)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
ffffffff81872bd0-ffffffff81872bea: warn_crc32c_csum_update (STB_LOCAL)
ffffffff8187abca-ffffffff8187abe2: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81911c8a)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
ffffffff81909c80-ffffffff81909c9a: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81911c8a-ffffffff81911ca2: warn_crc32c_csum_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
__wsum warn_crc32c_csum_update(const void *buff, int len, __wsum sum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81932dea)
Location: net/core/skbuff.c:2869
Inline: True
```
**Symbols:**

```
ffffffff8192ad80-ffffffff8192ad9a: warn_crc32c_csum_update (STB_LOCAL)
ffffffff81932dea-ffffffff81932e02: warn_crc32c_csum_update.cold (STB_LOCAL)
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
