# Function: <code>ext4_valid_block_bitmap</code>

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
In fs/ext4/balloc.c (ffffffff8128f095)
Location: fs/ext4/balloc.c:314
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
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
In fs/ext4/balloc.c (ffffffff812bc5c7)
Location: fs/ext4/balloc.c:317
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
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
In fs/ext4/balloc.c (ffffffff812d1c17)
Location: fs/ext4/balloc.c:317
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
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
In fs/ext4/balloc.c (ffffffff812e32cd)
Location: fs/ext4/balloc.c:317
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
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
In fs/ext4/balloc.c (ffffffff81307cb6)
Location: fs/ext4/balloc.c:318
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
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
In fs/ext4/balloc.c (ffffffff81335bab)
Location: fs/ext4/balloc.c:302
Inline: True
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
In fs/ext4/balloc.c (ffffffff8134ce2b)
Location: fs/ext4/balloc.c:302
Inline: True
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
In fs/ext4/balloc.c (ffffffff8137583b)
Location: fs/ext4/balloc.c:302
Inline: True
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
In fs/ext4/balloc.c (ffffffff8138da99)
Location: fs/ext4/balloc.c:310
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d8e50)
Location: fs/ext4/balloc.c:310
Inline: False
```
**Symbols:**

```
ffffffff813d8e50-ffffffff813d8f81: ext4_valid_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eaa60)
Location: fs/ext4/balloc.c:310
Inline: False
```
**Symbols:**

```
ffffffff813eaa60-ffffffff813eab91: ext4_valid_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f0f80)
Location: fs/ext4/balloc.c:310
Inline: False
```
**Symbols:**

```
ffffffff813f0f80-ffffffff813f10ba: ext4_valid_block_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:310
Inline: False
```
**Symbols:**

```
ffffffff81442ee0-ffffffff81443077: ext4_valid_block_bitmap (STB_LOCAL)
ffffffff81cc88b9-ffffffff81cc8a85: ext4_valid_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:310
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff814bed00-ffffffff814beeb0: ext4_valid_block_bitmap (STB_LOCAL)
ffffffff81e7b604-ffffffff81e7b7ca: ext4_valid_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:310
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff81556bf0-ffffffff81556d94: ext4_valid_block_bitmap (STB_LOCAL)
ffffffff8206bd92-ffffffff8206bf5b: ext4_valid_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:342
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff8158e9b0-ffffffff8158eb40: ext4_valid_block_bitmap (STB_LOCAL)
ffffffff820ebc20-ffffffff820ebdd1: ext4_valid_block_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_valid_block_bitmap(struct super_block *sb, struct ext4_group_desc *desc, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:344
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
**Symbols:**

```
ffffffff815c76c0-ffffffff815c7850: ext4_valid_block_bitmap (STB_LOCAL)
ffffffff821c8e84-ffffffff821c9035: ext4_valid_block_bitmap.cold (STB_LOCAL)
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
In fs/ext4/balloc.c (ffff80001045fa10)
Location: fs/ext4/balloc.c:310
Inline: True
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
In fs/ext4/balloc.c (c0620250)
Location: fs/ext4/balloc.c:310
Inline: True
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
In fs/ext4/balloc.c (c00000000057bcdc)
Location: fs/ext4/balloc.c:310
Inline: True
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
In fs/ext4/balloc.c (ffffffe0002ef17a)
Location: fs/ext4/balloc.c:310
Inline: True
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
In fs/ext4/balloc.c (ffffffff81386079)
Location: fs/ext4/balloc.c:310
Inline: True
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
In fs/ext4/balloc.c (ffffffff81376b09)
Location: fs/ext4/balloc.c:310
Inline: True
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
In fs/ext4/balloc.c (ffffffff81383b49)
Location: fs/ext4/balloc.c:310
Inline: True
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
In fs/ext4/balloc.c (ffffffff81397674)
Location: fs/ext4/balloc.c:310
Inline: True
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
