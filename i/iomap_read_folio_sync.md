# Function: <code>iomap_read_folio_sync</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int iomap_read_folio_sync(loff_t block_start, struct folio *folio, size_t poff, size_t plen, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81487f00)
Location: fs/iomap/buffered-io.c:534
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff81487f00-ffffffff81487fe3: iomap_read_folio_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_read_folio_sync(loff_t block_start, struct folio *folio, size_t poff, size_t plen, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151bb40)
Location: fs/iomap/buffered-io.c:514
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff8151bb40-ffffffff8151bc23: iomap_read_folio_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_read_folio_sync(loff_t block_start, struct folio *folio, size_t poff, size_t plen, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81553e50)
Location: fs/iomap/buffered-io.c:529
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff81553e50-ffffffff81553f33: iomap_read_folio_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomap_read_folio_sync(loff_t block_start, struct folio *folio, size_t poff, size_t plen, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81589e30)
Location: fs/iomap/buffered-io.c:621
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff81589e30-ffffffff81589f13: iomap_read_folio_sync (STB_LOCAL)
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
