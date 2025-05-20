# Function: <code>io_sequence_defer</code>

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
In fs/io_uring.c (ffffffff8132e137)
Location: fs/io_uring.c:427
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff813423c5)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/io_uring.c (ffff8000104024dc)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (c05d2fb4)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (c00000000050c5a0)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffe0002ae75c)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff8133a9a5)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff8132b6a5)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff81338475)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff8134a415)
Location: fs/io_uring.c:436
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
</ul>

## Differences
