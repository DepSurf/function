# Function: <code>iov_iter_restore</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void iov_iter_restore(struct iov_iter *i, struct iov_iter_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81619d90)
Location: lib/iov_iter.c:1991
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:kiocb_done
```
**Symbols:**

```
ffffffff81619d90-ffffffff81619e07: iov_iter_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iov_iter_restore(struct iov_iter *i, struct iov_iter_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e7250)
Location: lib/iov_iter.c:2040
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:kiocb_done
```
**Symbols:**

```
ffffffff816e7250-ffffffff816e72cd: iov_iter_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iov_iter_restore(struct iov_iter *i, struct iov_iter_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d6a70)
Location: lib/iov_iter.c:1892
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff817d6a70-ffffffff817d6b10: iov_iter_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iov_iter_restore(struct iov_iter *i, struct iov_iter_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81815a90)
Location: lib/iov_iter.c:1560
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff81815a90-ffffffff81815b11: iov_iter_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iov_iter_restore(struct iov_iter *i, struct iov_iter_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8185abd0)
Location: lib/iov_iter.c:1373
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff8185abd0-ffffffff8185ac51: iov_iter_restore (STB_GLOBAL)
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
