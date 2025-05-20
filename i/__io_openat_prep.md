# Function: <code>__io_openat_prep</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137b9a0)
Location: fs/io_uring.c:3054
Inline: False
```
**Symbols:**

```
ffffffff8137b9a0-ffffffff8137ba31: __io_openat_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a120)
Location: fs/io_uring.c:4024
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff8138a120-ffffffff8138a1b5: __io_openat_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390d60)
Location: fs/io_uring.c:3785
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff81390d60-ffffffff81390df1: __io_openat_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813debc0)
Location: fs/io_uring.c:4195
Inline: True
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff813debc0-ffffffff813dec82: __io_openat_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c7b40)
Location: io_uring/io_uring.c:5126
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_openat2_prep
  - io_uring/io_uring.c:io_openat_prep
```
**Symbols:**

```
ffffffff816c7b40-ffffffff816c7bfe: __io_openat_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/openclose.c (ffffffff817944f0)
Location: io_uring/openclose.c:34
Inline: False
Direct callers:
  - io_uring/openclose.c:io_openat2_prep
  - io_uring/openclose.c:io_openat_prep
```
**Symbols:**

```
ffffffff817944f0-ffffffff817945ae: __io_openat_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/openclose.c (ffffffff817d51a0)
Location: io_uring/openclose.c:45
Inline: False
Direct callers:
  - io_uring/openclose.c:io_openat2_prep
  - io_uring/openclose.c:io_openat_prep
```
**Symbols:**

```
ffffffff817d51a0-ffffffff817d5283: __io_openat_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __io_openat_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/openclose.c (ffffffff81818ff0)
Location: io_uring/openclose.c:50
Inline: False
Direct callers:
  - io_uring/openclose.c:io_openat2_prep
  - io_uring/openclose.c:io_openat_prep
```
**Symbols:**

```
ffffffff81818ff0-ffffffff818190d3: __io_openat_prep (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
