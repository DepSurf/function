# Function: <code>ext4_validate_block_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128ef90)
Location: fs/ext4/balloc.c:363
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff8128ef90-ffffffff8128f331: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bc4c0)
Location: fs/ext4/balloc.c:366
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff812bc4c0-ffffffff812bc850: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d1b10)
Location: fs/ext4/balloc.c:366
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff812d1b10-ffffffff812d1ea0: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e31d0)
Location: fs/ext4/balloc.c:366
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff812e31d0-ffffffff812e351e: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81307bc0)
Location: fs/ext4/balloc.c:367
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81307bc0-ffffffff81307f0e: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81335ab0)
Location: fs/ext4/balloc.c:357
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81335ab0-ffffffff81335df4: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134cd30)
Location: fs/ext4/balloc.c:357
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff8134cd30-ffffffff8134d074: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81375750)
Location: fs/ext4/balloc.c:357
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81375750-ffffffff81375a53: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138d9a0)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff8138d9a0-ffffffff8138dcc1: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d8f90)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff813d8f90-ffffffff813d9149: ext4_validate_block_bitmap.part.0 (STB_LOCAL)
ffffffff813d9150-ffffffff813d91c2: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eaba0)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff813eaba0-ffffffff813ead5e: ext4_validate_block_bitmap.part.0 (STB_LOCAL)
ffffffff813ead60-ffffffff813eae17: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f10c0)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff813f10c0-ffffffff813f127e: ext4_validate_block_bitmap.part.0 (STB_LOCAL)
ffffffff813f1280-ffffffff813f1341: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81443080)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81443080-ffffffff8144323e: ext4_validate_block_bitmap.part.0 (STB_LOCAL)
ffffffff81443240-ffffffff8144330e: ext4_validate_block_bitmap (STB_LOCAL)
ffffffff81cc8a85-ffffffff81cc8aaf: ext4_validate_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:365
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff814beeb0-ffffffff814bf0ed: ext4_validate_block_bitmap (STB_LOCAL)
ffffffff81e7b7ca-ffffffff81e7b7f3: ext4_validate_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:365
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81556db0-ffffffff81556fed: ext4_validate_block_bitmap (STB_LOCAL)
ffffffff8206bf5b-ffffffff8206bf84: ext4_validate_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8158ee10)
Location: fs/ext4/balloc.c:397
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff8158ee10-ffffffff8158f09d: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815c7b20)
Location: fs/ext4/balloc.c:399
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff815c7b20-ffffffff815c7dad: ext4_validate_block_bitmap (STB_LOCAL)
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
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff80001045f8f0)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffff80001045f8f0-ffff80001045fd20: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c062014c)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
c062014c-c06204f0: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057bbb0)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
c00000000057bbb0-c00000000057c06c: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002ef09a)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffe0002ef09a-ffffffe0002ef444: ext4_validate_block_bitmap (STB_LOCAL)
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
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81385f80)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81385f80-ffffffff813862a1: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376a10)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81376a10-ffffffff81376d31: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81383a50)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81383a50-ffffffff81383d71: ext4_validate_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_validate_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397570)
Location: fs/ext4/balloc.c:365
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
**Symbols:**

```
ffffffff81397570-ffffffff81397895: ext4_validate_block_bitmap (STB_LOCAL)
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
