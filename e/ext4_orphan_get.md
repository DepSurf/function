# Function: <code>ext4_orphan_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812955f0)
Location: fs/ext4/ialloc.c:1144
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812955f0-ffffffff812957fa: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812c2c30)
Location: fs/ext4/ialloc.c:1152
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812c2c30-ffffffff812c2e9e: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812d8220)
Location: fs/ext4/ialloc.c:1152
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812d8220-ffffffff812d848e: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812f65b0)
Location: fs/ext4/ialloc.c:1204
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812f65b0-ffffffff812f6899: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8131abe0)
Location: fs/ext4/ialloc.c:1232
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8131abe0-ffffffff8131aec9: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1207
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81349278-ffffffff81349309: ext4_orphan_get.cold.26 (STB_LOCAL)
ffffffff81348b70-ffffffff81348dea: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1207
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81361438-ffffffff813614c9: ext4_orphan_get.cold.27 (STB_LOCAL)
ffffffff81360d20-ffffffff81360fa9: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1207
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8138a4b8-ffffffff8138a55a: ext4_orphan_get.cold (STB_LOCAL)
ffffffff81389e20-ffffffff8138a050: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813a2f03-ffffffff813a2fa5: ext4_orphan_get.cold (STB_LOCAL)
ffffffff813a2840-ffffffff813a2a70: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ee880)
Location: fs/ext4/ialloc.c:1218
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff813ee880-ffffffff813eeb93: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81400fe0)
Location: fs/ext4/ialloc.c:1360
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff81400fe0-ffffffff81401302: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81407520)
Location: fs/ext4/ialloc.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff81407520-ffffffff81407843: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81459dc0)
Location: fs/ext4/ialloc.c:1368
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff81459dc0-ffffffff8145a0e3: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff814d7a60)
Location: fs/ext4/ialloc.c:1368
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff814d7a60-ffffffff814d7da5: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815707d0)
Location: fs/ext4/ialloc.c:1367
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff815707d0-ffffffff81570af2: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815a85c0)
Location: fs/ext4/ialloc.c:1369
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff815a85c0-ffffffff815a88c8: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815e1370)
Location: fs/ext4/ialloc.c:1369
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_cleanup
```
**Symbols:**

```
ffffffff815e1370-ffffffff815e1678: ext4_orphan_get (STB_GLOBAL)
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
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffff800010475e68)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff800010475e68-ffff8000104761c0: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c06378ac)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c06378ac-c0637bd4: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c000000000597c90)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c000000000597c90-c0000000005980dc: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe000301836)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe000301836-ffffffe000301b28: ext4_orphan_get (STB_GLOBAL)
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
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8139b4e3-ffffffff8139b585: ext4_orphan_get.cold (STB_LOCAL)
ffffffff8139ae20-ffffffff8139b050: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8138bf73-ffffffff8138c015: ext4_orphan_get.cold (STB_LOCAL)
ffffffff8138b8b0-ffffffff8138bae0: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81398d43-ffffffff81398de5: ext4_orphan_get.cold (STB_LOCAL)
ffffffff81398680-ffffffff813988b0: ext4_orphan_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct inode *ext4_orphan_get(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:1203
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813ad169-ffffffff813ad20b: ext4_orphan_get.cold (STB_LOCAL)
ffffffff813acaa0-ffffffff813accd0: ext4_orphan_get (STB_GLOBAL)
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
