# Function: <code>ext4_check_descriptors</code>

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
In fs/ext4/super.c (ffffffff812bceaa)
Location: fs/ext4/super.c:2119
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff812ebe57)
Location: fs/ext4/super.c:2238
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81301e1a)
Location: fs/ext4/super.c:2263
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81336d21)
Location: fs/ext4/super.c:2321
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff8135b2a4)
Location: fs/ext4/super.c:2324
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81389a38)
Location: fs/ext4/super.c:2365
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813a25b6)
Location: fs/ext4/super.c:2427
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ca480)
Location: fs/ext4/super.c:2470
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813ca480-ffffffff813ca955: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3830)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813e3830-ffffffff813e3d05: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81430ca0)
Location: fs/ext4/super.c:2642
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81430ca0-ffffffff8143116c: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81449a70)
Location: fs/ext4/super.c:2847
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81449a70-ffffffff81449f35: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144f3f0)
Location: fs/ext4/super.c:2873
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8144f3f0-ffffffff8144f8b2: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a2f70)
Location: fs/ext4/super.c:2859
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff814a2f70-ffffffff814a3432: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152a420)
Location: fs/ext4/super.c:3238
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff8152a420-ffffffff8152a8ff: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c8de0)
Location: fs/ext4/super.c:3227
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff815c8de0-ffffffff815c92bf: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81600ba0)
Location: fs/ext4/super.c:3281
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff81600ba0-ffffffff8160107c: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816398f0)
Location: fs/ext4/super.c:3287
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff816398f0-ffffffff81639dcc: ext4_check_descriptors (STB_LOCAL)
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
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bce40)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff8000104bce40-ffff8000104bd404: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c06804d0)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c06804d0-c0680af4: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f2e00)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c0000000005f2e00-c0000000005f3434: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000338b1a)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe000338b1a-ffffffe000338f92: ext4_check_descriptors (STB_LOCAL)
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
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dbe10)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813dbe10-ffffffff813dc2e5: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cc890)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813cc890-ffffffff813ccd65: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d92b0)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813d92b0-ffffffff813d9785: ext4_check_descriptors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block *sb, ext4_fsblk_t sb_block, ext4_group_t *first_not_zeroed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ee5b0)
Location: fs/ext4/super.c:2488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813ee5b0-ffffffff813eea65: ext4_check_descriptors (STB_LOCAL)
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
