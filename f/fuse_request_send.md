# Function: <code>fuse_request_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130de00)
Location: fs/fuse/dev.c:508
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff8130de00-ffffffff8130de29: fuse_request_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813420d0)
Location: fs/fuse/dev.c:483
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff813420d0-ffffffff813420f9: fuse_request_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81358020)
Location: fs/fuse/dev.c:487
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff81358020-ffffffff81358049: fuse_request_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136cc80)
Location: fs/fuse/dev.c:487
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff8136cc80-ffffffff8136cca9: fuse_request_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81394530)
Location: fs/fuse/dev.c:487
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff81394530-ffffffff81394559: fuse_request_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c3570)
Location: fs/fuse/dev.c:500
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_send_read
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffff813c3570-ffffffff813c359b: fuse_request_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813db170)
Location: fs/fuse/dev.c:556
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813db170-ffffffff813db19b: fuse_request_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814075f0)
Location: fs/fuse/dev.c:580
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814075f0-ffffffff8140761b: fuse_request_send (STB_GLOBAL)
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
