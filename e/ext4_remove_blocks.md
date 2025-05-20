# Function: <code>ext4_remove_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c677d)
Location: fs/ext4/extents.c:2476
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f6283)
Location: fs/ext4/extents.c:2498
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130c233)
Location: fs/ext4/extents.c:2498
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812eab1b)
Location: fs/ext4/extents.c:2499
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130f5be)
Location: fs/ext4/extents.c:2499
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133b041)
Location: fs/ext4/extents.c:2493
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813523c3)
Location: fs/ext4/extents.c:2524
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a7d0)
Location: fs/ext4/extents.c:2541
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8137a7d0-ffffffff8137ada3: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81392ca0)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81392ca0-ffffffff81393273: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813df200)
Location: fs/ext4/extents.c:2408
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff813df200-ffffffff813df68f: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f0ab0)
Location: fs/ext4/extents.c:2407
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff813f0ab0-ffffffff813f0f41: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f6f40)
Location: fs/ext4/extents.c:2410
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff813f6f40-ffffffff813f73c2: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2448
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81449c10-ffffffff8144a0c1: ext4_remove_blocks (STB_LOCAL)
ffffffff81cc9199-ffffffff81cc92af: ext4_remove_blocks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2447
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff814c6310-ffffffff814c681f: ext4_remove_blocks (STB_LOCAL)
ffffffff81e7be76-ffffffff81e7bf96: ext4_remove_blocks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2454
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8155e8a0-ffffffff8155ed85: ext4_remove_blocks (STB_LOCAL)
ffffffff8206c4d5-ffffffff8206c5eb: ext4_remove_blocks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2454
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81596690-ffffffff81596b4f: ext4_remove_blocks (STB_LOCAL)
ffffffff820ec378-ffffffff820ec42b: ext4_remove_blocks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2430
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff815cf340-ffffffff815cf7ff: ext4_remove_blocks (STB_LOCAL)
ffffffff821c95ac-ffffffff821c965f: ext4_remove_blocks.cold (STB_LOCAL)
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
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010465a80)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffff800010465a80-ffff800010465f90: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0625b0c)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
c0625b0c-c062614c: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000582eb0)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
c000000000582eb0-c0000000005834c0: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f3cae)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffe0002f3cae-ffffffe0002f411a: ext4_remove_blocks (STB_LOCAL)
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
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138b280)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8138b280-ffffffff8138b853: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137bd10)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8137bd10-ffffffff8137c2e3: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81388be0)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81388be0-ffffffff813891b3: ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t *handle, struct inode *inode, struct ext4_extent *ex, struct partial_cluster *partial, ext4_lblk_t from, ext4_lblk_t to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139c8f0)
Location: fs/ext4/extents.c:2587
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8139c8f0-ffffffff8139cedc: ext4_remove_blocks (STB_LOCAL)
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
