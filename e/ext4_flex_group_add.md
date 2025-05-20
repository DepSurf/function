# Function: <code>ext4_flex_group_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812bfa20)
Location: fs/ext4/resize.c:1407
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff812bfa20-ffffffff812c0eb9: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812eef70)
Location: fs/ext4/resize.c:1407
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff812eef70-ffffffff812f08b7: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81304f40)
Location: fs/ext4/resize.c:1407
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff81304f40-ffffffff81306887: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813205e0)
Location: fs/ext4/resize.c:1408
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813205e0-ffffffff8132137a: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81344cd0)
Location: fs/ext4/resize.c:1434
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff81344cd0-ffffffff81345ab5: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1437
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff81372b50-ffffffff813738f3: ext4_flex_group_add (STB_LOCAL)
ffffffff81375205-ffffffff81375227: ext4_flex_group_add.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1437
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8138afa0-ffffffff8138bd22: ext4_flex_group_add (STB_LOCAL)
ffffffff8138d61d-ffffffff8138d63f: ext4_flex_group_add.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1445
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813b63b0-ffffffff813b6870: ext4_flex_group_add (STB_LOCAL)
ffffffff813b7982-ffffffff813b79a0: ext4_flex_group_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813cf2e0-ffffffff813cf796: ext4_flex_group_add (STB_LOCAL)
ffffffff813d0ccd-ffffffff813d0ceb: ext4_flex_group_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141c0e0)
Location: fs/ext4/resize.c:1458
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8141c0e0-ffffffff8141c384: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142fe60)
Location: fs/ext4/resize.c:1466
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8142fe60-ffffffff8143013c: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff814369c0)
Location: fs/ext4/resize.c:1466
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff814369c0-ffffffff81436d99: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8148a5f0)
Location: fs/ext4/resize.c:1476
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8148a5f0-ffffffff8148a9d1: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8150e410)
Location: fs/ext4/resize.c:1499
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8150e410-ffffffff8150e8b0: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815a9280)
Location: fs/ext4/resize.c:1534
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff815a9280-ffffffff815a9717: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815dfae0)
Location: fs/ext4/resize.c:1533
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff815dfae0-ffffffff815dff77: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff816185b0)
Location: fs/ext4/resize.c:1535
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff816185b0-ffffffff81618a51: ext4_flex_group_add (STB_LOCAL)
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
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a7bf0)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffff8000104a7bf0-ffff8000104a80d0: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0669dc4)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
c0669dc4-c066a424: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d5010)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
c0000000005d5010-c0000000005d5d40: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000327f06)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffe000327f06-ffffffe000328808: ext4_flex_group_add (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813c78c0-ffffffff813c7d76: ext4_flex_group_add (STB_LOCAL)
ffffffff813c92ad-ffffffff813c92cb: ext4_flex_group_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813b8340-ffffffff813b87f6: ext4_flex_group_add (STB_LOCAL)
ffffffff813b9d2d-ffffffff813b9d4b: ext4_flex_group_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813c4d50-ffffffff813c5206: ext4_flex_group_add (STB_LOCAL)
ffffffff813c673d-ffffffff813c675b: ext4_flex_group_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_flex_group_add(struct super_block *sb, struct inode *resize_inode, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1480
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813d9f40-ffffffff813da43a: ext4_flex_group_add (STB_LOCAL)
ffffffff813db96d-ffffffff813db98d: ext4_flex_group_add.cold (STB_LOCAL)
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
