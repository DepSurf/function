# Function: <code>filemap_fdatawrite_wbc</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite_wbc(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299460)
Location: mm/filemap.c:390
Inline: True
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_flush
  - mm/filemap.c:filemap_fdatawrite_range
  - mm/filemap.c:filemap_fdatawrite
```
**Symbols:**

```
ffffffff81299460-ffffffff81299528: filemap_fdatawrite_wbc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite_wbc(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef4d0)
Location: mm/filemap.c:378
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
**Symbols:**

```
ffffffff812ef4d0-ffffffff812ef574: filemap_fdatawrite_wbc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite_wbc(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135a210)
Location: mm/filemap.c:378
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
**Symbols:**

```
ffffffff8135a210-ffffffff8135a2b4: filemap_fdatawrite_wbc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite_wbc(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138bc20)
Location: mm/filemap.c:383
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
**Symbols:**

```
ffffffff8138bc20-ffffffff8138bcc4: filemap_fdatawrite_wbc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite_wbc(struct address_space *mapping, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b5750)
Location: mm/filemap.c:378
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
**Symbols:**

```
ffffffff813b5750-ffffffff813b57f4: filemap_fdatawrite_wbc (STB_GLOBAL)
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
