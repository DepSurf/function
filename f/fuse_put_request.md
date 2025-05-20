# Function: <code>fuse_put_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130ee60)
Location: fs/fuse/dev.c:289
Inline: True
Direct callers:
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff8130ee60-ffffffff8130ef77: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81343270)
Location: fs/fuse/dev.c:269
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff81343270-ffffffff81343381: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81359080)
Location: fs/fuse/dev.c:269
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff81359080-ffffffff81359191: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136d890)
Location: fs/fuse/dev.c:269
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff8136d890-ffffffff8136d9a5: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81392460)
Location: fs/fuse/dev.c:269
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_put_super
```
**Symbols:**

```
ffffffff81392460-ffffffff81392579: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c1400)
Location: fs/fuse/dev.c:282
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffff813c1400-ffffffff813c152c: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813daa50)
Location: fs/fuse/dev.c:324
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813daa50-ffffffff813dac00: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81406631)
Location: fs/fuse/dev.c:326
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8140951c-ffffffff8140952f: fuse_put_request.cold (STB_LOCAL)
ffffffff81406610-ffffffff814067d9: fuse_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141fa50)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8141fa50-ffffffff8141faf2: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146e460)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8146e460-ffffffff8146e53b: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_put_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81488bd0)
Location: fs/fuse/dev.c:158
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81488bd0-ffffffff81488cae: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_put_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148e4d0)
Location: fs/fuse/dev.c:158
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8148e4d0-ffffffff8148e5ae: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_put_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e5f40)
Location: fs/fuse/dev.c:158
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff814e5f40-ffffffff814e601e: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_put_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81574380)
Location: fs/fuse/dev.c:158
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81574380-ffffffff81574486: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_put_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81619c10)
Location: fs/fuse/dev.c:158
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81619c10-ffffffff81619d05: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_put_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81651dc0)
Location: fs/fuse/dev.c:158
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81651dc0-ffffffff81651eb5: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_put_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168b3d0)
Location: fs/fuse/dev.c:158
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8168b3d0-ffffffff8168b4c5: fuse_put_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010502310)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffff800010502310-ffff800010502410: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06be74c)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_retrieve
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
c06be74c-c06be810: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c0000000006465b0)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
c0000000006465b0-c000000000646720: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036f39c)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffe00036f39c-ffffffe00036f49e: fuse_put_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81418030)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81418030-ffffffff814180d2: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408ab0)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81408ab0-ffffffff81408b52: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814141d0)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff814141d0-ffffffff81414272: fuse_put_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fuse_put_request(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142ae90)
Location: fs/fuse/dev.c:156
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8142ae90-ffffffff8142af30: fuse_put_request (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fuse_conn *fc</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, req</code> ➡️ <code>req</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
