# Function: <code>io_alloc_file_tables</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813987ed)
Location: fs/io_uring.c:7479
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ec7ff)
Location: fs/io_uring.c:7906
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e9151a)
Location: io_uring/io_uring.c:9219
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sqe_files_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_alloc_file_tables(struct io_file_table *table, unsigned int nr_files);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff817940e0)
Location: io_uring/filetable.c:36
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff817940e0-ffffffff81794147: io_alloc_file_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_alloc_file_tables(struct io_file_table *table, unsigned int nr_files);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff817d4dc0)
Location: io_uring/filetable.c:39
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff817d4dc0-ffffffff817d4e27: io_alloc_file_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_alloc_file_tables(struct io_file_table *table, unsigned int nr_files);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff81818c10)
Location: io_uring/filetable.c:39
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff81818c10-ffffffff81818c77: io_alloc_file_tables (STB_GLOBAL)
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
