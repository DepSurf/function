# Function: <code>fat_get_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fb580)
Location: fs/fat/inode.c:163
Inline: False
```
**Symbols:**

```
ffffffff812fb580-ffffffff812fb77b: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81331870)
Location: fs/fat/inode.c:169
Inline: False
```
**Symbols:**

```
ffffffff81331870-ffffffff81331a7b: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81347610)
Location: fs/fat/inode.c:169
Inline: False
```
**Symbols:**

```
ffffffff81347610-ffffffff8134781b: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8135c040)
Location: fs/fat/inode.c:169
Inline: False
```
**Symbols:**

```
ffffffff8135c040-ffffffff8135c24d: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81380d40)
Location: fs/fat/inode.c:169
Inline: False
```
**Symbols:**

```
ffffffff81380d40-ffffffff81380f4d: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:176
Inline: False
```
**Symbols:**

```
ffffffff813af4d0-ffffffff813af6ef: fat_get_block (STB_LOCAL)
ffffffff813b00a2-ffffffff813b00ec: fat_get_block.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:176
Inline: False
```
**Symbols:**

```
ffffffff813c8970-ffffffff813c8b94: fat_get_block (STB_LOCAL)
ffffffff813c950a-ffffffff813c9554: fat_get_block.cold.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:177
Inline: False
```
**Symbols:**

```
ffffffff813f3510-ffffffff813f3716: fat_get_block (STB_LOCAL)
ffffffff813f40ae-ffffffff813f40fb: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
ffffffff8140d3f0-ffffffff8140d5f6: fat_get_block (STB_LOCAL)
ffffffff8140df80-ffffffff8140dfcd: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8145b2f0)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff8145b2f0-ffffffff8145b369: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81477640)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff81477640-ffffffff814776b9: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8147d0c0)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff8147d0c0-ffffffff8147d139: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff814d4810-ffffffff814d48b2: fat_get_block (STB_LOCAL)
ffffffff81cd0441-ffffffff81cd048b: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff81561780-ffffffff81561832: fat_get_block (STB_LOCAL)
ffffffff81e83660-ffffffff81e836aa: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff81603e80-ffffffff81603f32: fat_get_block (STB_LOCAL)
ffffffff82072392-ffffffff820723dc: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff8163bda0-ffffffff8163be52: fat_get_block (STB_LOCAL)
ffffffff820f1fb5-ffffffff820f1fff: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:183
Inline: False
```
**Symbols:**

```
ffffffff81675300-ffffffff816753b2: fat_get_block (STB_LOCAL)
ffffffff821cf297-ffffffff821cf2e1: fat_get_block.cold (STB_LOCAL)
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
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104ee0e8)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
ffff8000104ee0e8-ffff8000104ee368: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06abc58)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
c06abc58-c06abf8c: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062cf70)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
c00000000062cf70-c00000000062d2dc: fat_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035e530)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
ffffffe00035e530-ffffffe00035e702: fat_get_block (STB_LOCAL)
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
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
ffffffff814059d0-ffffffff81405bd6: fat_get_block (STB_LOCAL)
ffffffff81406560-ffffffff814065ad: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
ffffffff813f6450-ffffffff813f6656: fat_get_block (STB_LOCAL)
ffffffff813f6fe0-ffffffff813f702d: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
ffffffff81402d50-ffffffff81402f56: fat_get_block (STB_LOCAL)
ffffffff814038e0-ffffffff8140392d: fat_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:182
Inline: False
```
**Symbols:**

```
ffffffff814189b0-ffffffff81418bb6: fat_get_block (STB_LOCAL)
ffffffff81419550-ffffffff8141959d: fat_get_block.cold (STB_LOCAL)
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
