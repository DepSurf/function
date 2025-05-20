# Function: <code>io_import_fixed</code>

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
In fs/io_uring.c (ffffffff8132d927)
Location: fs/io_uring.c:1079
Inline: True
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
In fs/io_uring.c (ffffffff81340960)
Location: fs/io_uring.c:1160
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t io_import_fixed(struct io_kiocb *req, int rw, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137b4c0)
Location: fs/io_uring.c:2244
Inline: False
Direct callers:
  - fs/io_uring.c:io_import_iovec
```
**Symbols:**

```
ffffffff8137b4c0-ffffffff8137b5f0: io_import_fixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t io_import_fixed(struct io_kiocb *req, int rw, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813896b0)
Location: fs/io_uring.c:3001
Inline: False
Direct callers:
  - fs/io_uring.c:io_import_iovec
```
**Symbols:**

```
ffffffff813896b0-ffffffff813897d9: io_import_fixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813946d6)
Location: fs/io_uring.c:2855
Inline: True
Inline callers:
  - fs/io_uring.c:io_import_iovec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e1ef6)
Location: fs/io_uring.c:3077
Inline: True
Inline callers:
  - fs/io_uring.c:io_import_iovec
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
In io_uring/io_uring.c (ffffffff816ccfe3)
Location: io_uring/io_uring.c:3571
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_import_iovec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_import_fixed(int ddir, struct iov_iter *iter, struct io_mapped_ubuf *imu, u64 buf_addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2ef0)
Location: io_uring/rsrc.c:1327
Inline: False
Direct callers:
  - io_uring/uring_cmd.c:io_uring_cmd_import_fixed
  - io_uring/net.c:io_send_zc
  - io_uring/rw.c:__io_import_iovec
```
**Symbols:**

```
ffffffff817a2ef0-ffffffff817a3014: io_import_fixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_import_fixed(int ddir, struct iov_iter *iter, struct io_mapped_ubuf *imu, u64 buf_addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e3e90)
Location: io_uring/rsrc.c:1217
Inline: False
Direct callers:
  - io_uring/uring_cmd.c:io_uring_cmd_import_fixed
  - io_uring/net.c:io_send_zc
  - io_uring/rw.c:__io_import_iovec
```
**Symbols:**

```
ffffffff817e3e90-ffffffff817e3fc5: io_import_fixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_import_fixed(int ddir, struct iov_iter *iter, struct io_mapped_ubuf *imu, u64 buf_addr, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81827f40)
Location: io_uring/rsrc.c:1059
Inline: False
Direct callers:
  - io_uring/uring_cmd.c:io_uring_cmd_import_fixed
  - io_uring/net.c:io_send_zc
  - io_uring/rw.c:__io_import_iovec
```
**Symbols:**

```
ffffffff81827f40-ffffffff81828075: io_import_fixed (STB_GLOBAL)
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
In fs/io_uring.c (ffff80001040091c)
Location: fs/io_uring.c:1160
Inline: True
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
In fs/io_uring.c (c05d237c)
Location: fs/io_uring.c:1160
Inline: True
Inline callers:
  - fs/io_uring.c:io_import_iovec
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
In fs/io_uring.c (c00000000050a28c)
Location: fs/io_uring.c:1160
Inline: True
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
In fs/io_uring.c (ffffffe0002acfb2)
Location: fs/io_uring.c:1160
Inline: True
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
In fs/io_uring.c (ffffffff81338f40)
Location: fs/io_uring.c:1160
Inline: True
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
In fs/io_uring.c (ffffffff81329c70)
Location: fs/io_uring.c:1160
Inline: True
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
In fs/io_uring.c (ffffffff81336a10)
Location: fs/io_uring.c:1160
Inline: True
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
In fs/io_uring.c (ffffffff81349ae0)
Location: fs/io_uring.c:1160
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
