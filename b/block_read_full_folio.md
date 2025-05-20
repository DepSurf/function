# Function: <code>block_read_full_folio</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int block_read_full_folio(struct folio *folio, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2254
Inline: False
Direct callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:blkdev_read_folio
```
**Symbols:**

```
ffffffff81e77058-ffffffff81e77103: block_read_full_folio.cold (STB_LOCAL)
ffffffff81445fa0-ffffffff81446373: block_read_full_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int block_read_full_folio(struct folio *folio, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2239
Inline: False
Direct callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:blkdev_read_folio
```
**Symbols:**

```
ffffffff82069134-ffffffff820691df: block_read_full_folio.cold (STB_LOCAL)
ffffffff814d4f20-ffffffff814d531e: block_read_full_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int block_read_full_folio(struct folio *folio, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2375
Inline: False
Direct callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:blkdev_read_folio
```
**Symbols:**

```
ffffffff820e89e6-ffffffff820e8ac7: block_read_full_folio.cold (STB_LOCAL)
ffffffff8150aef0-ffffffff8150b340: block_read_full_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int block_read_full_folio(struct folio *folio, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153fe20)
Location: fs/buffer.c:2346
Inline: False
Direct callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:blkdev_read_folio
```
**Symbols:**

```
ffffffff8153fe20-ffffffff81540197: block_read_full_folio (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
