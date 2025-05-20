# Function: <code>descriptor_loc</code>

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
In fs/ext4/super.c (ffffffff812bcd14)
Location: fs/ext4/super.c:2429
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
In fs/ext4/super.c (ffffffff812ebcbb)
Location: fs/ext4/super.c:2574
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
In fs/ext4/super.c (ffffffff81301c72)
Location: fs/ext4/super.c:2601
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81338fbd)
Location: fs/ext4/super.c:2680
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81338fbd-ffffffff81339047: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135ccdd)
Location: fs/ext4/super.c:2683
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8135ccdd-ffffffff8135cd67: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d7c0)
Location: fs/ext4/super.c:2755
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8137d7c0-ffffffff8137d859: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395f70)
Location: fs/ext4/super.c:2817
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81395f70-ffffffff81396009: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bff20)
Location: fs/ext4/super.c:2856
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813bff20-ffffffff813bffbd: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d91f0)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813d91f0-ffffffff813d928d: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814260b0)
Location: fs/ext4/super.c:3028
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff814260b0-ffffffff8142614d: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143d4b0)
Location: fs/ext4/super.c:3233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8143d4b0-ffffffff8143d54d: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814432f0)
Location: fs/ext4/super.c:3263
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff814432f0-ffffffff8144338a: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496f60)
Location: fs/ext4/super.c:3086
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81496f60-ffffffff81496ffa: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81522150)
Location: fs/ext4/super.c:3481
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff81522150-ffffffff815221ff: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815beb90)
Location: fs/ext4/super.c:3470
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff815beb90-ffffffff815bec42: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f5930)
Location: fs/ext4/super.c:3524
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff815f5930-ffffffff815f59e2: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162e240)
Location: fs/ext4/super.c:3530
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff8162e240-ffffffff8162e2f2: descriptor_loc (STB_LOCAL)
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
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac880)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff8000104ac880-ffff8000104ac948: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674eb4)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c0674eb4-c0674f64: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e47a0)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c0000000005e47a0-c0000000005e48b4: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00032fc3c)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe00032fc3c-ffffffe00032fcf0: descriptor_loc (STB_LOCAL)
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
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d17d0)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813d17d0-ffffffff813d186d: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c2250)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813c2250-ffffffff813c22ed: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cec60)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813cec60-ffffffff813cecfd: descriptor_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block *sb, ext4_fsblk_t logical_sb_block, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3eb0)
Location: fs/ext4/super.c:2874
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813e3eb0-ffffffff813e3f4d: descriptor_loc (STB_LOCAL)
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
