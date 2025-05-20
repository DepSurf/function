# Function: <code>__bh_read</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bh_read(struct buffer_head *bh, blk_opf_t op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3030)
Location: fs/buffer.c:2964
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff814d3030-ffffffff814d30b8: __bh_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bh_read(struct buffer_head *bh, blk_opf_t op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81509c50)
Location: fs/buffer.c:3102
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81509c50-ffffffff81509cd8: __bh_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bh_read(struct buffer_head *bh, blk_opf_t op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153ea80)
Location: fs/buffer.c:3062
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_load_superblock
```
**Symbols:**

```
ffffffff8153ea80-ffffffff8153eb08: __bh_read (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
