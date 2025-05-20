# Function: <code>ext4_ext_rm_leaf</code>

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
Location: fs/ext4/extents.c:2592
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
In fs/ext4/extents.c (ffffffff812f620f)
Location: fs/ext4/extents.c:2614
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
In fs/ext4/extents.c (ffffffff8130c1bf)
Location: fs/ext4/extents.c:2614
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
In fs/ext4/extents.c (ffffffff812eaaa7)
Location: fs/ext4/extents.c:2615
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
In fs/ext4/extents.c (ffffffff8130f546)
Location: fs/ext4/extents.c:2615
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, long long int *partial_cluster, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133aee0)
Location: fs/ext4/extents.c:2609
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8133aee0-ffffffff8133b79b: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81352270)
Location: fs/ext4/extents.c:2660
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81352270-ffffffff81352e4b: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137bb80)
Location: fs/ext4/extents.c:2677
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8137bb80-ffffffff8137c222: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81394050)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81394050-ffffffff813946f2: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dff60)
Location: fs/ext4/extents.c:2544
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813dff60-ffffffff813e05fd: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f1820)
Location: fs/ext4/extents.c:2543
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813f1820-ffffffff813f1e7a: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f7ca0)
Location: fs/ext4/extents.c:2546
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813f7ca0-ffffffff813f82f3: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2584
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8144a180-ffffffff8144a7f5: ext4_ext_rm_leaf (STB_LOCAL)
ffffffff81cc92af-ffffffff81cc934f: ext4_ext_rm_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2583
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff814c68d0-ffffffff814c6fda: ext4_ext_rm_leaf (STB_LOCAL)
ffffffff81e7bf96-ffffffff81e7c05e: ext4_ext_rm_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2590
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8155eed0-ffffffff8155f5db: ext4_ext_rm_leaf (STB_LOCAL)
ffffffff8206c5eb-ffffffff8206c6b3: ext4_ext_rm_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2590
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81596c90-ffffffff81597346: ext4_ext_rm_leaf (STB_LOCAL)
ffffffff820ec42b-ffffffff820ec4a2: ext4_ext_rm_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2566
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff815cf940-ffffffff815cfff6: ext4_ext_rm_leaf (STB_LOCAL)
ffffffff821c965f-ffffffff821c96d6: ext4_ext_rm_leaf.cold (STB_LOCAL)
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
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010466da0)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffff800010466da0-ffff8000104673c4: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c06278b8)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
c06278b8-c0628014: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000584eb0)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
c000000000584eb0-c00000000058575c: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f4d4a)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffe0002f4d4a-ffffffe0002f52de: ext4_ext_rm_leaf (STB_LOCAL)
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
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138c630)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8138c630-ffffffff8138ccd2: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137d0c0)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8137d0c0-ffffffff8137d762: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389f90)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81389f90-ffffffff8138a632: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct partial_cluster *partial, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139dcc0)
Location: fs/ext4/extents.c:2723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8139dcc0-ffffffff8139e37b: ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct partial_cluster *partial</code>
</li>
<li>
<b>Param removed. </b>
<code>long long int *partial_cluster</code>
</li>
</ul>
</details>
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
