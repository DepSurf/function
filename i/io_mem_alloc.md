# Function: <code>io_mem_alloc</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813310f1)
Location: fs/io_uring.c:2816
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81344cdd)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137c6d3)
Location: fs/io_uring.c:7168
Inline: True
Inline callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_allocate_scq_urings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *io_mem_alloc(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a200)
Location: fs/io_uring.c:8336
Inline: False
Direct callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_allocate_scq_urings
```
**Symbols:**

```
ffffffff8138a200-ffffffff8138a229: io_mem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *io_mem_alloc(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390e00)
Location: fs/io_uring.c:8121
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff81390e00-ffffffff81390e29: io_mem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *io_mem_alloc(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de2c0)
Location: fs/io_uring.c:8834
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff813de2c0-ffffffff813de2e9: io_mem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *io_mem_alloc(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8f0ba)
Location: io_uring/io_uring.c:10124
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
```
**Symbols:**

```
ffffffff81e8f0ba-ffffffff81e8f0e7: io_mem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *io_mem_alloc(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81788aa0)
Location: io_uring/io_uring.c:2595
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
```
**Symbols:**

```
ffffffff81788aa0-ffffffff81788ad1: io_mem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *io_mem_alloc(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c9480)
Location: io_uring/io_uring.c:2743
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
```
**Symbols:**

```
ffffffff817c9480-ffffffff817c94c1: io_mem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *io_mem_alloc(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81816590)
Location: io_uring/io_uring.c:2803
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/kbuf.c:io_register_pbuf_ring
```
**Symbols:**

```
ffffffff81816590-ffffffff818165d1: io_mem_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff80001040303c)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d655c)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050f9c4)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002b087a)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133d2bd)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132df7d)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133ad8d)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134df3d)
Location: fs/io_uring.c:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
