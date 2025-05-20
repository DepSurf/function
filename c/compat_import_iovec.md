# Function: <code>compat_import_iovec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fdc50)
Location: lib/iov_iter.c:819
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_do_readv_writev
  - fs/aio.c:aio_run_iocb
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff813fdc50-ffffffff813fdd24: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81445340)
Location: lib/iov_iter.c:775
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_do_readv_writev
  - fs/aio.c:aio_run_iocb
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81445340-ffffffff81445414: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81463b30)
Location: lib/iov_iter.c:1289
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_do_readv_writev
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81463b30-ffffffff81463c04: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81468be0)
Location: lib/iov_iter.c:1413
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81468be0-ffffffff81468cb4: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81494e90)
Location: lib/iov_iter.c:1415
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81494e90-ffffffff81494f64: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814ca160)
Location: lib/iov_iter.c:1545
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff814ca160-ffffffff814ca234: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814deeb0)
Location: lib/iov_iter.c:1641
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff814deeb0-ffffffff814def5d: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150ab30)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff8150ab30-ffffffff8150abda: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81528b40)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81528b40-ffffffff81528c30: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587f50)
Location: lib/iov_iter.c:1697
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81587f50-ffffffff81588037: compat_import_iovec (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff8000106334c8)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffff8000106334c8-ffff800010633590: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d87c0)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
c0000000007d87c0-c0000000007d88bc: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81521120)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81521120-ffffffff81521210: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81511410)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81511410-ffffffff81511500: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151d1b0)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff8151d1b0-ffffffff8151d2a0: compat_import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81536a20)
Location: lib/iov_iter.c:1662
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_readv
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/compat.c:compat_keyctl_instantiate_key_iov
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81536a20-ffffffff81536b10: compat_import_iovec (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
