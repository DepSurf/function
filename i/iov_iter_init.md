# Function: <code>iov_iter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb250)
Location: lib/iov_iter.c:346
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_single_range
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff813fb250-ffffffff813fb28a: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8144251d)
Location: lib/iov_iter.c:319
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff814424a0-ffffffff814424da: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145f96d)
Location: lib/iov_iter.c:411
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff8145f6b0-ffffffff8145f6ea: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464fad)
Location: lib/iov_iter.c:431
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff814649b0-ffffffff814649ea: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490f2d)
Location: lib/iov_iter.c:431
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff81490930-ffffffff8149096a: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6178)
Location: lib/iov_iter.c:431
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff814c5730-ffffffff814c576a: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814d9e60)
Location: lib/iov_iter.c:435
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff814d9e60-ffffffff814d9ea9: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:436
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff8150abda-ffffffff8150ac0b: iov_iter_init.cold (STB_LOCAL)
ffffffff81505640-ffffffff81505699: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81524094)
Location: lib/iov_iter.c:436
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff81523620-ffffffff81523667: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587c54)
Location: lib/iov_iter.c:441
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
  - fs/read_write.c:new_sync_read
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff81586bd0-ffffffff81586c17: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a4cd0)
Location: lib/iov_iter.c:448
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
  - fs/read_write.c:new_sync_read
  - fs/seq_file.c:seq_read
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff815a3ec0-ffffffff815a3ee9: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ab4dc)
Location: lib/iov_iter.c:490
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
  - fs/read_write.c:new_sync_read
  - fs/seq_file.c:seq_read
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff815aadd0-ffffffff815aadfc: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614afc)
Location: lib/iov_iter.c:464
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
  - fs/read_write.c:new_sync_read
  - fs/seq_file.c:seq_read
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff81614100-ffffffff8161412a: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e0cf2)
Location: lib/iov_iter.c:508
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
  - fs/read_write.c:new_sync_read
  - fs/seq_file.c:seq_read
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:__io_import_iovec
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff816e0a10-ffffffff816e0a4a: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d1202)
Location: lib/iov_iter.c:424
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - io_uring/net.c:io_recvmsg
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff817d0d50-ffffffff817d0d8e: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff818158f9)
Location: lib/iov_iter.c:284
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff8180f9b0-ffffffff8180f9f2: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8185aa45)
Location: lib/iov_iter.c:162
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff81855630-ffffffff8185566d: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d460)
Location: lib/iov_iter.c:436
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffff80001062d460-ffff80001062d4b4: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d3f8c)
Location: lib/iov_iter.c:436
Inline: False
Direct callers:
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_write
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_iovec
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
c07d3f8c-c07d4008: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0550)
Location: lib/iov_iter.c:436
Inline: False
Direct callers:
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
c0000000007d0550-c0000000007d05c0: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d2e0)
Location: lib/iov_iter.c:436
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_iovec
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffe00045d2e0-ffffffe00045d328: iov_iter_init (STB_GLOBAL)
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
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c674)
Location: lib/iov_iter.c:436
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff8151bc00-ffffffff8151bc47: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c964)
Location: lib/iov_iter.c:436
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff8150bef0-ffffffff8150bf37: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518704)
Location: lib/iov_iter.c:436
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff81517c90-ffffffff81517cd7: iov_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_init(struct iov_iter *i, unsigned int direction, const struct iovec *iov, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531a44)
Location: lib/iov_iter.c:436
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_iovec
Direct callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
**Symbols:**

```
ffffffff81531430-ffffffff81531477: iov_iter_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int direction</code> ➡️ <code>unsigned int direction</code>
</li>
</ul>
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
