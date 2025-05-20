# Function: <code>__fat_get_block</code>

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
In fs/fat/inode.c (ffffffff812fb586)
Location: fs/fat/inode.c:111
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff81331876)
Location: fs/fat/inode.c:111
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff81347616)
Location: fs/fat/inode.c:111
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff8135c046)
Location: fs/fat/inode.c:111
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff81380d46)
Location: fs/fat/inode.c:111
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff813af510)
Location: fs/fat/inode.c:112
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff813c89b2)
Location: fs/fat/inode.c:112
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff813f354c)
Location: fs/fat/inode.c:113
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff8140d42c)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff8145b120-ffffffff8145b2ef: __fat_get_block (STB_LOCAL)
ffffffff8145bd5f-ffffffff8145bdaa: __fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81477470-ffffffff8147763f: __fat_get_block (STB_LOCAL)
ffffffff81bedca6-ffffffff81bedcf1: __fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff8147cee0-ffffffff8147d0b7: __fat_get_block (STB_LOCAL)
ffffffff81bdfdb0-ffffffff81bdfdfb: __fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff814d4600-ffffffff814d4810: __fat_get_block (STB_LOCAL)
ffffffff81cd0365-ffffffff81cd0441: __fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81561550-ffffffff81561773: __fat_get_block (STB_LOCAL)
ffffffff81e83592-ffffffff81e83660: __fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81603c00-ffffffff81603e68: __fat_get_block (STB_LOCAL)
ffffffff82072309-ffffffff82072392: __fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff8163bb20-ffffffff8163bd88: __fat_get_block (STB_LOCAL)
ffffffff820f1f2c-ffffffff820f1fb5: __fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __fat_get_block(struct inode *inode, sector_t iblock, long unsigned int *max_blocks, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:119
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81675080-ffffffff816752e8: __fat_get_block (STB_LOCAL)
ffffffff821cf20e-ffffffff821cf297: __fat_get_block.cold (STB_LOCAL)
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
In fs/fat/inode.c (ffff8000104ee130)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (c06abcc4)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (c00000000062cfd8)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffe00035e562)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff81405a0c)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff813f648c)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff81402d8c)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/fat/inode.c (ffffffff814189ec)
Location: fs/fat/inode.c:118
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
