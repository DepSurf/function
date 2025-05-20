# Function: <code>ext4_read_inline_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812dfb90)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_read_inline_dir
```
**Symbols:**

```
ffffffff812dfb90-ffffffff812dfcac: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8130f840)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8130f840-ffffffff8130f95c: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81325660)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff81325660-ffffffff8132577c: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812f9620)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff812f9620-ffffffff812f9754: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131dc60)
Location: fs/ext4/inline.c:165
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8131dc60-ffffffff8131dd94: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134bc40)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8134bc40-ffffffff8134bd63: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81363d80)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff81363d80-ffffffff81363ea3: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138cc90)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8138cc90-ffffffff8138cdb7: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a56e0)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff813a56e0-ffffffff813a5807: ext4_read_inline_data (STB_LOCAL)
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
In fs/ext4/inline.c (ffffffff813f4244)
Location: fs/ext4/inline.c:164
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff813f1510-ffffffff813f160f: ext4_read_inline_data.part.0.isra.0 (STB_LOCAL)
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
In fs/ext4/inline.c (ffffffff814069d4)
Location: fs/ext4/inline.c:164
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff81403bf0-ffffffff81403cef: ext4_read_inline_data.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140a350)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8140a350-ffffffff8140a47f: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145ce20)
Location: fs/ext4/inline.c:165
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8145ce20-ffffffff8145cf4f: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814dae50)
Location: fs/ext4/inline.c:169
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff814dae50-ffffffff814dafcd: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815742f0)
Location: fs/ext4/inline.c:169
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff815742f0-ffffffff8157446d: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ac140)
Location: fs/ext4/inline.c:178
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_folio
```
**Symbols:**

```
ffffffff815ac140-ffffffff815ac2bd: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e4ed0)
Location: fs/ext4/inline.c:178
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_folio
```
**Symbols:**

```
ffffffff815e4ed0-ffffffff815e504d: ext4_read_inline_data (STB_LOCAL)
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
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff800010478ca0)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffff800010478ca0-ffff800010478d80: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063ac04)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
c063ac04-c063acc4: ext4_read_inline_data (STB_LOCAL)
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
In fs/ext4/inline.c (c00000000059efac)
Location: fs/ext4/inline.c:164
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
c00000000059bb30-c00000000059bc38: ext4_read_inline_data.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000303fe0)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffe000303fe0-ffffffe0003040ac: ext4_read_inline_data (STB_LOCAL)
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
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139dcc0)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8139dcc0-ffffffff8139dde7: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138e750)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8138e750-ffffffff8138e877: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139b520)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff8139b520-ffffffff8139b647: ext4_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_inline_data(struct inode *inode, void *buffer, unsigned int len, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813af9e0)
Location: fs/ext4/inline.c:164
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_read_inline_page
```
**Symbols:**

```
ffffffff813af9e0-ffffffff813afb07: ext4_read_inline_data (STB_LOCAL)
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
