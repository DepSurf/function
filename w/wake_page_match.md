# Function: <code>wake_page_match</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812592c5)
Location: include/linux/pagemap.h:574
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In fs/io_uring.c (ffffffff8138e8b5)
Location: include/linux/pagemap.h:574
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_buf_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125cbc5)
Location: include/linux/pagemap.h:590
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In fs/io_uring.c (ffffffff81393ed9)
Location: include/linux/pagemap.h:590
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_buf_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81298b15)
Location: include/linux/pagemap.h:589
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In fs/io_uring.c (ffffffff813def39)
Location: include/linux/pagemap.h:589
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_buf_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef185)
Location: include/linux/pagemap.h:871
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In io_uring/io_uring.c (ffffffff816cf349)
Location: include/linux/pagemap.h:871
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_async_buf_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81359c95)
Location: include/linux/pagemap.h:867
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In io_uring/rw.c (ffffffff817a3519)
Location: include/linux/pagemap.h:867
Inline: True
Inline callers:
  - io_uring/rw.c:io_async_buf_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138b5d5)
Location: include/linux/pagemap.h:888
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In io_uring/rw.c (ffffffff817e44b9)
Location: include/linux/pagemap.h:888
Inline: True
Inline callers:
  - io_uring/rw.c:io_async_buf_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b50f5)
Location: include/linux/pagemap.h:978
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In io_uring/rw.c (ffffffff81828589)
Location: include/linux/pagemap.h:978
Inline: True
Inline callers:
  - io_uring/rw.c:io_async_buf_func
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
