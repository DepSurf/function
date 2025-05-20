# Function: <code>io_rw_should_reissue</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_rw_should_reissue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813931a0)
Location: fs/io_uring.c:2461
Inline: False
Direct callers:
  - fs/io_uring.c:io_complete_rw_iopoll
```
**Symbols:**

```
ffffffff813931a0-ffffffff8139323b: io_rw_should_reissue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_rw_should_reissue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e11f0)
Location: fs/io_uring.c:2661
Inline: False
Direct callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
**Symbols:**

```
ffffffff813e11f0-ffffffff813e128b: io_rw_should_reissue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_rw_should_reissue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cc270)
Location: io_uring/io_uring.c:3187
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_complete_rw_common
```
**Symbols:**

```
ffffffff816cc270-ffffffff816cc31a: io_rw_should_reissue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_rw_should_reissue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a3030)
Location: io_uring/rw.c:187
Inline: False
Direct callers:
  - io_uring/rw.c:io_complete_rw_iopoll
```
**Symbols:**

```
ffffffff817a3030-ffffffff817a30da: io_rw_should_reissue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_rw_should_reissue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e3fe0)
Location: io_uring/rw.c:187
Inline: False
Direct callers:
  - io_uring/rw.c:io_complete_rw_iopoll
```
**Symbols:**

```
ffffffff817e3fe0-ffffffff817e408d: io_rw_should_reissue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_rw_should_reissue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff81828090)
Location: io_uring/rw.c:206
Inline: False
Direct callers:
  - io_uring/rw.c:__io_complete_rw_common
```
**Symbols:**

```
ffffffff81828090-ffffffff8182813d: io_rw_should_reissue (STB_LOCAL)
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
