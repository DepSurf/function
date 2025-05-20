# Function: <code>fuse_request_send_background</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813115d0)
Location: fs/fuse/dev.c:610
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813115d0-ffffffff81311648: fuse_request_send_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81345a40)
Location: fs/fuse/dev.c:585
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81345a40-ffffffff81345ab8: fuse_request_send_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8135b760)
Location: fs/fuse/dev.c:589
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8135b760-ffffffff8135b7d8: fuse_request_send_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813700f0)
Location: fs/fuse/dev.c:588
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813700f0-ffffffff81370165: fuse_request_send_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81394df0)
Location: fs/fuse/dev.c:588
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81394df0-ffffffff81394e6a: fuse_request_send_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c3f10)
Location: fs/fuse/dev.c:601
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_send_read
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813c3f10-ffffffff813c3f8d: fuse_request_send_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dd700)
Location: fs/fuse/dev.c:660
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813dd700-ffffffff813dd75b: fuse_request_send_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_request_send_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81409260)
Location: fs/fuse/dev.c:684
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8140958e-ffffffff814095a1: fuse_request_send_background.cold (STB_LOCAL)
ffffffff81409230-ffffffff81409290: fuse_request_send_background (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
