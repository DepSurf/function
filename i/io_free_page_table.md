# Function: <code>io_free_page_table</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e0e07)
Location: fs/io_uring.c:7682
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_data_alloc
  - fs/io_uring.c:io_rsrc_data_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_free_page_table(void **table, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e60b)
Location: io_uring/io_uring.c:8991
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_rsrc_data_alloc
  - io_uring/io_uring.c:io_rsrc_data_free
```
**Symbols:**

```
ffffffff81e8e60b-ffffffff81e8e659: io_free_page_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a074e)
Location: io_uring/rsrc.c:367
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_data_alloc
  - io_uring/rsrc.c:io_rsrc_data_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e1a46)
Location: io_uring/rsrc.c:271
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_data_alloc
  - io_uring/rsrc.c:io_rsrc_data_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81825e05)
Location: io_uring/rsrc.c:276
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_data_alloc
  - io_uring/rsrc.c:io_rsrc_data_free
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
</ul>
