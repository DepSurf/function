# Function: <code>splice_folio_into_pipe</code>

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
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t splice_folio_into_pipe(struct pipe_inode_info *pipe, struct folio *folio, loff_t fpos, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2846
Inline: False
Direct callers:
  - mm/filemap.c:filemap_splice_read
  - mm/shmem.c:shmem_file_splice_read
```
**Symbols:**

```
ffffffff820e1a78-ffffffff820e1ab2: splice_folio_into_pipe.cold (STB_LOCAL)
ffffffff81392340-ffffffff81392494: splice_folio_into_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t splice_folio_into_pipe(struct pipe_inode_info *pipe, struct folio *folio, loff_t fpos, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2793
Inline: False
Direct callers:
  - mm/filemap.c:filemap_splice_read
  - mm/shmem.c:shmem_file_splice_read
```
**Symbols:**

```
ffffffff821be4b0-ffffffff821be4e7: splice_folio_into_pipe.cold (STB_LOCAL)
ffffffff813bbf80-ffffffff813bc0d0: splice_folio_into_pipe (STB_GLOBAL)
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
