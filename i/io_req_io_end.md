# Function: <code>io_req_io_end</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_req_io_end(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a39c0)
Location: io_uring/rw.c:241
Inline: True
Direct callers:
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
```
**Symbols:**

```
ffffffff817a39c0-ffffffff817a3b36: io_req_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_req_io_end(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e49f0)
Location: io_uring/rw.c:241
Inline: True
Direct callers:
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
```
**Symbols:**

```
ffffffff817e49f0-ffffffff817e4b9e: io_req_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_req_io_end(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff81828ed0)
Location: io_uring/rw.c:255
Inline: True
Direct callers:
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
  - io_uring/rw.c:__io_complete_rw_common
```
**Symbols:**

```
ffffffff81828ed0-ffffffff81829000: io_req_io_end (STB_LOCAL)
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
