# Function: <code>ext4_wait_block_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f480)
Location: fs/ext4/balloc.c:486
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff8128f480-ffffffff8128f51c: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bc990)
Location: fs/ext4/balloc.c:489
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff812bc990-ffffffff812bca2c: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d1fe0)
Location: fs/ext4/balloc.c:489
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff812d1fe0-ffffffff812d207c: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e3650)
Location: fs/ext4/balloc.c:489
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff812e3650-ffffffff812e36ed: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81308040)
Location: fs/ext4/balloc.c:490
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff81308040-ffffffff813080dd: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81335f30)
Location: fs/ext4/balloc.c:497
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff81335f30-ffffffff81335fde: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d1b0)
Location: fs/ext4/balloc.c:497
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff8134d1b0-ffffffff8134d25e: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81375b90)
Location: fs/ext4/balloc.c:497
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff81375b90-ffffffff81375c54: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138de00)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff8138de00-ffffffff8138dec4: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813da205)
Location: fs/ext4/balloc.c:506
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff813d9310-ffffffff813d93cb: ext4_wait_block_bitmap.part.0 (STB_LOCAL)
ffffffff813d93d0-ffffffff813d93eb: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813ebed7)
Location: fs/ext4/balloc.c:518
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff813eafa0-ffffffff813eb05e: ext4_wait_block_bitmap.part.0 (STB_LOCAL)
ffffffff813eb060-ffffffff813eb07b: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f14d0)
Location: fs/ext4/balloc.c:518
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff813f14d0-ffffffff813f15ac: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814434d0)
Location: fs/ext4/balloc.c:518
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff814434d0-ffffffff814435ac: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814bf2f0)
Location: fs/ext4/balloc.c:519
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff814bf2f0-ffffffff814bf3e7: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81557230)
Location: fs/ext4/balloc.c:519
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff81557230-ffffffff81557325: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8158f0b0)
Location: fs/ext4/balloc.c:561
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff8158f0b0-ffffffff8158f1a5: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815c7dc0)
Location: fs/ext4/balloc.c:566
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff815c7dc0-ffffffff815c7eb5: ext4_wait_block_bitmap (STB_GLOBAL)
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
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff80001045fed8)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffff80001045fed8-ffff80001045ffe0: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c06206f4)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
c06206f4-c06207e4: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057c210)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
c00000000057c210-c00000000057c35c: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002ef5ce)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffe0002ef5ce-ffffffe0002ef69e: ext4_wait_block_bitmap (STB_GLOBAL)
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
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813863e0)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff813863e0-ffffffff813864a4: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376e70)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff81376e70-ffffffff81376f34: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81383eb0)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff81383eb0-ffffffff81383f74: ext4_wait_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_wait_block_bitmap(struct super_block *sb, ext4_group_t block_group, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397a20)
Location: fs/ext4/balloc.c:505
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
**Symbols:**

```
ffffffff81397a20-ffffffff81397adf: ext4_wait_block_bitmap (STB_GLOBAL)
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
