# Function: <code>io_prep_rw</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d5d0)
Location: fs/io_uring.c:1003
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff8132d5d0-ffffffff8132d818: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81340650)
Location: fs/io_uring.c:1073
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81340650-ffffffff813408d7: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137b270)
Location: fs/io_uring.c:2151
Inline: False
```
**Symbols:**

```
ffffffff8137b270-ffffffff8137b4ba: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389ef0)
Location: fs/io_uring.c:2903
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff81389ef0-ffffffff8138a11f: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391030)
Location: fs/io_uring.c:2676
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff81391030-ffffffff813912f0: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e2de0)
Location: fs/io_uring.c:2885
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff813e2de0-ffffffff813e30cd: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cac70)
Location: io_uring/io_uring.c:3407
Inline: False
```
**Symbols:**

```
ffffffff816cac70-ffffffff816cadba: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a3f20)
Location: io_uring/rw.c:76
Inline: False
```
**Symbols:**

```
ffffffff817a3f20-ffffffff817a40e1: io_prep_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e4f80)
Location: io_uring/rw.c:76
Inline: False
```
**Symbols:**

```
ffffffff817e4f80-ffffffff817e5123: io_prep_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff81829420)
Location: io_uring/rw.c:77
Inline: False
Direct callers:
  - io_uring/rw.c:io_read_mshot_prep
  - io_uring/rw.c:io_prep_rw_fixed
  - io_uring/rw.c:io_prep_rwv
```
**Symbols:**

```
ffffffff81829420-ffffffff81829530: io_prep_rw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffff8000104005c8)
Location: fs/io_uring.c:1073
Inline: True
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffff8000104005c8-ffff800010400860: io_prep_rw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d1ff8)
Location: fs/io_uring.c:1073
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
c05d1ff8-c05d2270: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (c000000000509e00)
Location: fs/io_uring.c:1073
Inline: True
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
c000000000509e00-c00000000050a1d8: io_prep_rw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffe0002acd24)
Location: fs/io_uring.c:1073
Inline: True
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffe0002acd24-ffffffe0002acf3e: io_prep_rw.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338c30)
Location: fs/io_uring.c:1073
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81338c30-ffffffff81338eb7: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81329960)
Location: fs/io_uring.c:1073
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81329960-ffffffff81329be7: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336700)
Location: fs/io_uring.c:1073
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81336700-ffffffff81336987: io_prep_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_prep_rw(struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813497d0)
Location: fs/io_uring.c:1073
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff813497d0-ffffffff81349a57: io_prep_rw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sqe_submit *s</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool force_nonblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
