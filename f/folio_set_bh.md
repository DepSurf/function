# Function: <code>folio_set_bh</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void folio_set_bh(struct buffer_head *bh, struct folio *folio, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81509ded)
Location: fs/buffer.c:1557
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
```
**Symbols:**

```
ffffffff820e88e4-ffffffff820e88fd: folio_set_bh.cold (STB_LOCAL)
ffffffff81509520-ffffffff81509591: folio_set_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void folio_set_bh(struct buffer_head *bh, struct folio *folio, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8153ebd3)
Location: fs/buffer.c:1537
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
Direct callers:
  - mm/migrate.c:__buffer_migrate_folio
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff821c571e-ffffffff821c5736: folio_set_bh.cold (STB_LOCAL)
ffffffff8153e5b0-ffffffff8153e62f: folio_set_bh (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
