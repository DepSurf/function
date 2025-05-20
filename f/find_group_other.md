# Function: <code>find_group_other</code>

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
In fs/ext4/ialloc.c (ffffffff81294394)
Location: fs/ext4/ialloc.c:591
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff812c1962)
Location: fs/ext4/ialloc.c:591
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff812d6f9f)
Location: fs/ext4/ialloc.c:591
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff812f52c6)
Location: fs/ext4/ialloc.c:592
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff81319a2f)
Location: fs/ext4/ialloc.c:593
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff8134779f)
Location: fs/ext4/ialloc.c:563
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff8135f94f)
Location: fs/ext4/ialloc.c:563
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81388b02)
Location: fs/ext4/ialloc.c:563
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813a1477)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ec6d0)
Location: fs/ext4/ialloc.c:563
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813ec6d0-ffffffff813ec937: find_group_other (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813fe910)
Location: fs/ext4/ialloc.c:567
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813fe910-ffffffff813feb77: find_group_other (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81404d00)
Location: fs/ext4/ialloc.c:568
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81404d00-ffffffff81404f60: find_group_other (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:570
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff814574f0-ffffffff8145775c: find_group_other (STB_LOCAL)
ffffffff81cca288-ffffffff81cca2a6: find_group_other.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:570
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff814d5040-ffffffff814d52be: find_group_other (STB_LOCAL)
ffffffff81e7cfc0-ffffffff81e7cfde: find_group_other.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:569
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8156dd20-ffffffff8156df9e: find_group_other (STB_LOCAL)
ffffffff8206d5a3-ffffffff8206d5c1: find_group_other.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:569
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff815a5c10-ffffffff815a5e8c: find_group_other (STB_LOCAL)
ffffffff820ed2fc-ffffffff820ed314: find_group_other.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int find_group_other(struct super_block *sb, struct inode *parent, ext4_group_t *group, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:569
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff815dea80-ffffffff815decfc: find_group_other (STB_LOCAL)
ffffffff821ca442-ffffffff821ca45a: find_group_other.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffff800010474c90)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0636298)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c000000000596488)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe0003006ca)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81399a57)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8138a4e7)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813972b7)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ab5db)
Location: fs/ext4/ialloc.c:561
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
