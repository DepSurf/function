# Function: <code>iomap_to_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126e0bb)
Location: fs/buffer.c:1897
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff81281314)
Location: fs/buffer.c:1939
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff8128ebfe)
Location: fs/buffer.c:1936
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff812b17de)
Location: fs/buffer.c:1896
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff812d956b)
Location: fs/buffer.c:1867
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff812eea3b)
Location: fs/buffer.c:1875
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff81310233)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff81323203)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b920)
Location: fs/buffer.c:1920
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff8135b920-ffffffff8135ba40: iomap_to_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369ed0)
Location: fs/buffer.c:1919
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff81369ed0-ffffffff81369ff0: iomap_to_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f050)
Location: fs/buffer.c:1939
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff8136f050-ffffffff8136f170: iomap_to_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1918
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff813bdc90-ffffffff813bde10: iomap_to_bh (STB_LOCAL)
ffffffff81cc4489-ffffffff81cc44cf: iomap_to_bh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1914
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff81442960-ffffffff81442ac4: iomap_to_bh (STB_LOCAL)
ffffffff81e76cab-ffffffff81e76cf1: iomap_to_bh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1899
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff814d1960-ffffffff814d1ac7: iomap_to_bh (STB_LOCAL)
ffffffff82068e5e-ffffffff82068ea4: iomap_to_bh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2036
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff81508070-ffffffff815081d5: iomap_to_bh (STB_LOCAL)
ffffffff820e877e-ffffffff820e87c4: iomap_to_bh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_to_bh(struct inode *inode, sector_t block, struct buffer_head *bh, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2001
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_begin_int
```
**Symbols:**

```
ffffffff8153cdd0-ffffffff8153cf4c: iomap_to_bh (STB_LOCAL)
ffffffff821c555d-ffffffff821c55a3: iomap_to_bh.cold (STB_LOCAL)
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
In fs/buffer.c (ffff8000103dc578)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (c05b5840)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (c0000000004e1970)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffe000294728)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff8131b7e3)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff8130c383)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff813192b3)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
In fs/buffer.c (ffffffff8132aef1)
Location: fs/buffer.c:1876
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap *iomap</code> ➡️ <code>const struct iomap *iomap</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
