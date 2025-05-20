# Function: <code>csum_block_add_ext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81704d70)
Location: include/net/checksum.h:97
Inline: False
```
**Symbols:**

```
ffffffff81704d70-ffffffff81704d97: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176b950)
Location: include/net/checksum.h:100
Inline: False
```
**Symbols:**

```
ffffffff8176b950-ffffffff8176b968: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81798a20)
Location: include/net/checksum.h:100
Inline: False
```
**Symbols:**

```
ffffffff81798a20-ffffffff81798a38: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b6fe0)
Location: include/net/checksum.h:100
Inline: False
```
**Symbols:**

```
ffffffff817b6fe0-ffffffff817b6ff8: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182f5e0)
Location: include/net/checksum.h:100
Inline: False
```
**Symbols:**

```
ffffffff8182f5e0-ffffffff8182f5f8: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879a70)
Location: include/net/checksum.h:100
Inline: False
```
**Symbols:**

```
ffffffff81879a70-ffffffff81879a88: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189a6c0)
Location: include/net/checksum.h:100
Inline: False
```
**Symbols:**

```
ffffffff8189a6c0-ffffffff8189a6d8: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5f9d)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff818e4da0-ffffffff818e4db3: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819180eb)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81916f30-ffffffff81916f43: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb25b)
Location: include/net/checksum.h:90
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff819e98f0-ffffffff819e9903: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eaf7b)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff819e9690-ffffffff819e96a3: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d14a5)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff819cf7b0-ffffffff819cf7c3: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80f65)
Location: include/net/checksum.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81a7f320-ffffffff81a7f333: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf5a16)
Location: include/net/checksum.h:100
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81bf35f0-ffffffff81bf360d: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3c46)
Location: include/net/checksum.h:100
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81da1320-ffffffff81da133d: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e128a7)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81e0fbf0-ffffffff81e0fc0d: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecfa67)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81ecc6a0-ffffffff81ecc6bd: csum_block_add_ext (STB_LOCAL)
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
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0500)
Location: include/net/checksum.h:96
Inline: False
```
**Symbols:**

```
ffff800010bb0500-ffff800010bb0518: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccd8c4)
Location: include/net/checksum.h:96
Inline: False
```
**Symbols:**

```
c0ccd8c4-c0ccd8ec: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87110)
Location: include/net/checksum.h:96
Inline: False
```
**Symbols:**

```
c000000000c87110-c000000000c87134: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741316)
Location: include/net/checksum.h:96
Inline: False
```
**Symbols:**

```
ffffffe000741316-ffffffe00074133e: csum_block_add_ext (STB_LOCAL)
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
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b80eb)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff818b6f30-ffffffff818b6f43: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187203b)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81870e80-ffffffff81870e93: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819090eb)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81907f30-ffffffff81907f43: csum_block_add_ext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__wsum csum_block_add_ext(__wsum csum, __wsum csum2, int offset, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192a1af)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
```
**Symbols:**

```
ffffffff81928f70-ffffffff81928f83: csum_block_add_ext (STB_LOCAL)
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
