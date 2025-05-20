# Function: <code>ext4_add_dirent_to_inline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e0310)
Location: fs/ext4/inline.c:996
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff812e0310-ffffffff812e0438: ext4_add_dirent_to_inline.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8130ffe0)
Location: fs/ext4/inline.c:997
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8130ffe0-ffffffff81310109: ext4_add_dirent_to_inline.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff81325be0)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81325be0-ffffffff81325ce8: ext4_add_dirent_to_inline.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff812f9c20)
Location: fs/ext4/inline.c:1018
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff812f9c20-ffffffff812f9d20: ext4_add_dirent_to_inline.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131e250)
Location: fs/ext4/inline.c:1009
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8131e250-ffffffff8131e350: ext4_add_dirent_to_inline.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134c450)
Location: fs/ext4/inline.c:1012
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8134c450-ffffffff8134c57b: ext4_add_dirent_to_inline.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff81364590)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81364590-ffffffff813646bb: ext4_add_dirent_to_inline.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138ce80)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8138ce80-ffffffff8138cfad: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a58d0)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813a58d0-ffffffff813a5a07: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f1820)
Location: fs/ext4/inline.c:1015
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813f1820-ffffffff813f1957: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81404340)
Location: fs/ext4/inline.c:1015
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81404340-ffffffff81404483: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140a920)
Location: fs/ext4/inline.c:1021
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8140a920-ffffffff8140aa66: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145d570)
Location: fs/ext4/inline.c:1028
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8145d570-ffffffff8145d6c0: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814db7a0)
Location: fs/ext4/inline.c:1024
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff814db7a0-ffffffff814db909: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81574190)
Location: fs/ext4/inline.c:1023
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81574190-ffffffff815742d7: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815abfe0)
Location: fs/ext4/inline.c:1005
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff815abfe0-ffffffff815ac127: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e4d80)
Location: fs/ext4/inline.c:1004
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff815e4d80-ffffffff815e4ebc: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffff8000104790a0)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffff8000104790a0-ffff80001047921c: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_add_dirent_to_inline(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_iloc *iloc, void *inline_start, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063adc8)
Location: fs/ext4/inline.c:1015
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
c063adc8-c063af7c: ext4_add_dirent_to_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (c00000000059bc50)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
c00000000059bc50-c00000000059be10: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffe000304428)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffe000304428-ffffffe000304522: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139deb0)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8139deb0-ffffffff8139dfe7: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138e940)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8138e940-ffffffff8138ea77: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139b710)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8139b710-ffffffff8139b847: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff813afbd0)
Location: fs/ext4/inline.c:1015
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813afbd0-ffffffff813afd07: ext4_add_dirent_to_inline.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
