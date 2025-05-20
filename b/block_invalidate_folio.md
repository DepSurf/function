# Function: <code>block_invalidate_folio</code>

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
void block_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1498
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81e76e7f-ffffffff81e76eb2: block_invalidate_folio.cold (STB_LOCAL)
ffffffff81444260-ffffffff81444495: block_invalidate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void block_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1483
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8206901c-ffffffff8206904f: block_invalidate_folio.cold (STB_LOCAL)
ffffffff814d34a0-ffffffff814d3639: block_invalidate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void block_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1610
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff820e89b3-ffffffff820e89e6: block_invalidate_folio.cold (STB_LOCAL)
ffffffff8150a730-ffffffff8150a8c9: block_invalidate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void block_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1590
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff821c57e7-ffffffff821c5818: block_invalidate_folio.cold (STB_LOCAL)
ffffffff8153f6e0-ffffffff8153f876: block_invalidate_folio (STB_GLOBAL)
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
