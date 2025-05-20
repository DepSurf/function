# Function: <code>__io_splice_prep</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __io_splice_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137e9a0)
Location: fs/io_uring.c:2860
Inline: True
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8137e9a0-ffffffff8137eaac: __io_splice_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __io_splice_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81394520)
Location: fs/io_uring.c:3842
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff81394520-ffffffff81394682: __io_splice_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __io_splice_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813935d0)
Location: fs/io_uring.c:3611
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff813935d0-ffffffff81393644: __io_splice_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __io_splice_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e19e0)
Location: fs/io_uring.c:4019
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff813e19e0-ffffffff813e1ab2: __io_splice_prep (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff816c5cb9)
Location: io_uring/io_uring.c:4910
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_splice_prep
  - io_uring/io_uring.c:io_tee_prep
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
In io_uring/splice.c (ffffffff817938a9)
Location: io_uring/splice.c:26
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_tee_prep
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
In io_uring/splice.c (ffffffff817d45c9)
Location: io_uring/splice.c:26
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_tee_prep
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
In io_uring/splice.c (ffffffff81818439)
Location: io_uring/splice.c:26
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_tee_prep
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
</ul>
