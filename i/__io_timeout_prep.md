# Function: <code>__io_timeout_prep</code>

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
int __io_timeout_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool is_timeout_link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d5560)
Location: io_uring/io_uring.c:7466
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_link_timeout_prep
  - io_uring/io_uring.c:io_timeout_prep
```
**Symbols:**

```
ffffffff816d5560-ffffffff816d5753: __io_timeout_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_timeout_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool is_timeout_link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817991a0)
Location: io_uring/timeout.c:458
Inline: False
Direct callers:
  - io_uring/timeout.c:io_link_timeout_prep
  - io_uring/timeout.c:io_timeout_prep
```
**Symbols:**

```
ffffffff817991a0-ffffffff8179934a: __io_timeout_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_timeout_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool is_timeout_link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817da230)
Location: io_uring/timeout.c:498
Inline: False
Direct callers:
  - io_uring/timeout.c:io_link_timeout_prep
  - io_uring/timeout.c:io_timeout_prep
```
**Symbols:**

```
ffffffff817da230-ffffffff817da404: __io_timeout_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __io_timeout_prep(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool is_timeout_link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181e520)
Location: io_uring/timeout.c:492
Inline: False
Direct callers:
  - io_uring/timeout.c:io_link_timeout_prep
  - io_uring/timeout.c:io_timeout_prep
```
**Symbols:**

```
ffffffff8181e520-ffffffff8181e6f4: __io_timeout_prep (STB_LOCAL)
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
