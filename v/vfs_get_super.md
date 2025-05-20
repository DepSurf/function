# Function: <code>vfs_get_super</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf540)
Location: fs/super.c:1156
Inline: False
Direct callers:
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff812cf540-ffffffff812cf5ef: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e1820)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffff812e1820-ffffffff812e191a: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318548)
Location: fs/super.c:1162
Inline: True
Inline callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
Direct callers:
  - fs/super.c:get_tree_single_reconf
```
**Symbols:**

```
ffffffff81318b90-ffffffff81318c8a: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323918)
Location: fs/super.c:1109
Inline: True
Inline callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
Direct callers:
  - fs/super.c:get_tree_single_reconf
```
**Symbols:**

```
ffffffff813240d0-ffffffff813241ca: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813299d8)
Location: fs/super.c:1111
Inline: True
Inline callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
Direct callers:
  - fs/super.c:get_tree_single_reconf
```
**Symbols:**

```
ffffffff8132a1a0-ffffffff8132a29a: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81377008)
Location: fs/super.c:1111
Inline: True
Inline callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
Direct callers:
  - fs/super.c:get_tree_single_reconf
```
**Symbols:**

```
ffffffff813777d0-ffffffff813778ca: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6288)
Location: fs/super.c:1110
Inline: True
Inline callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
Direct callers:
  - fs/super.c:get_tree_single_reconf
```
**Symbols:**

```
ffffffff813f6a60-ffffffff813f6b5e: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, bool reconf, int (*test)(struct super_block *, struct fs_context *), int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147fba0)
Location: fs/super.c:1128
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffff8147fba0-ffffffff8147fc93: vfs_get_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, bool reconf, int (*test)(struct super_block *, struct fs_context *), int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4890)
Location: fs/super.c:1139
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffff814b4890-ffffffff814b4983: vfs_get_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e5dd8)
Location: fs/super.c:1255
Inline: True
Inline callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
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
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388bc0)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffff800010388bc0-ffff800010388ce8: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0571220)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
c0571220-c0571314: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047fac0)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
c00000000047fac0-c00000000047fc6c: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025b134)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffe00025b134-ffffffe00025b21e: vfs_get_super (STB_GLOBAL)
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
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9e00)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffff812d9e00-ffffffff812d9efa: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812caa80)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffff812caa80-ffffffff812cab7a: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7c10)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffff812d7c10-ffffffff812d7d0a: vfs_get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_get_super(struct fs_context *fc, enum vfs_get_super_keying keying, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8a50)
Location: fs/super.c:1162
Inline: False
Direct callers:
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single_reconf
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
```
**Symbols:**

```
ffffffff812e8a50-ffffffff812e8b4a: vfs_get_super (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reconf</code>
</li>
<li>
<b>Param added. </b>
<code>int (*test)(struct super_block *, struct fs_context *)</code>
</li>
<li>
<b>Param removed. </b>
<code>enum vfs_get_super_keying keying</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, keying, fill_super</code> ➡️ <code>fc, reconf, test, fill_super</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
