# Function: <code>ext4_try_merge_freed_extent</code>

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
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8130a670)
Location: fs/ext4/mballoc.c:4630
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff8130a670-ffffffff8130a72a: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8132f150)
Location: fs/ext4/mballoc.c:4630
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff8132f150-ffffffff8132f20a: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8135d7f0)
Location: fs/ext4/mballoc.c:4600
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff8135d7f0-ffffffff8135d8aa: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813760c0)
Location: fs/ext4/mballoc.c:4599
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff813760c0-ffffffff8137617a: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8139f5a0)
Location: fs/ext4/mballoc.c:4600
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff8139f5a0-ffffffff8139f668: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b8410)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff813b8410-ffffffff813b84d8: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81403a60)
Location: fs/ext4/mballoc.c:4864
Inline: True
```
**Symbols:**

```
ffffffff81403a60-ffffffff81403b09: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81416c90)
Location: fs/ext4/mballoc.c:5048
Inline: True
```
**Symbols:**

```
ffffffff81416c90-ffffffff81416d39: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141d9f0)
Location: fs/ext4/mballoc.c:5581
Inline: True
```
**Symbols:**

```
ffffffff8141d9f0-ffffffff8141da98: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81470480)
Location: fs/ext4/mballoc.c:5648
Inline: True
```
**Symbols:**

```
ffffffff81470480-ffffffff81470528: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814efe50)
Location: fs/ext4/mballoc.c:5703
Inline: True
```
**Symbols:**

```
ffffffff814efe50-ffffffff814efefc: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81589f80)
Location: fs/ext4/mballoc.c:5672
Inline: True
```
**Symbols:**

```
ffffffff81589f80-ffffffff8158a02c: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c2038)
Location: fs/ext4/mballoc.c:6309
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff815c0720-ffffffff815c07cc: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815fab68)
Location: fs/ext4/mballoc.c:6269
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff815f94c0-ffffffff815f956c: ext4_try_merge_freed_extent.part.0 (STB_LOCAL)
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
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff80001048f5b8)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffff80001048f5b8-ffff80001048f6f0: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c064f1b8)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
c064f1b8-c064f298: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005b5150)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
c0000000005b5150-c0000000005b52e0: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe000313b42)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffe000313b42-ffffffe000313c46: ext4_try_merge_freed_extent (STB_LOCAL)
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
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b09f0)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff813b09f0-ffffffff813b0ab8: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a1480)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff813a1480-ffffffff813a1548: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813ae250)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff813ae250-ffffffff813ae318: ext4_try_merge_freed_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ext4_try_merge_freed_extent(struct ext4_sb_info *sbi, struct ext4_free_data *entry, struct ext4_free_data *new_entry, struct rb_root *entry_rb_root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c2860)
Location: fs/ext4/mballoc.c:4619
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
**Symbols:**

```
ffffffff813c2860-ffffffff813c2926: ext4_try_merge_freed_extent (STB_LOCAL)
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
