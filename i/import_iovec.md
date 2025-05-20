# Function: <code>import_iovec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb6e0)
Location: lib/iov_iter.c:796
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:do_readv_writev
  - fs/splice.c:vmsplice_to_user
  - fs/aio.c:aio_run_iocb
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff813fb6e0-ffffffff813fb7b4: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442a90)
Location: lib/iov_iter.c:752
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:do_readv_writev
  - fs/splice.c:vmsplice_to_user
  - fs/aio.c:aio_run_iocb
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff81442a90-ffffffff81442b64: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145fca0)
Location: lib/iov_iter.c:1266
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:do_readv_writev
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff8145fca0-ffffffff8145fd74: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464d60)
Location: lib/iov_iter.c:1390
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff81464d60-ffffffff81464e34: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490ce0)
Location: lib/iov_iter.c:1392
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff81490ce0-ffffffff81490db4: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c5af0)
Location: lib/iov_iter.c:1522
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff814c5af0-ffffffff814c5bc4: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da2a0)
Location: lib/iov_iter.c:1618
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff814da2a0-ffffffff814da34d: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81505ad0)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff81505ad0-ffffffff81505b7a: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81523a70)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff81523a70-ffffffff81523b60: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587e60)
Location: lib/iov_iter.c:1674
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81587e60-ffffffff81587f47: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a8fa0)
Location: lib/iov_iter.c:1809
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - mm/madvise.c:__do_sys_process_madvise
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff815a8fa0-ffffffff815a8fd3: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b3be0)
Location: lib/iov_iter.c:2097
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - mm/madvise.c:__do_sys_process_madvise
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff815b3be0-ffffffff815b3c13: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81619d50)
Location: lib/iov_iter.c:1955
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - mm/madvise.c:__do_sys_process_madvise
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81619d50-ffffffff81619d83: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e7220)
Location: lib/iov_iter.c:2004
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - mm/madvise.c:__do_sys_process_madvise
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff816e7220-ffffffff816e724f: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d6a30)
Location: lib/iov_iter.c:1856
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - mm/madvise.c:__do_sys_process_madvise
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - net/socket.c:copy_msghdr_from_user
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff817d6a30-ffffffff817d6a5f: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81815a50)
Location: lib/iov_iter.c:1515
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - mm/madvise.c:__do_sys_process_madvise
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - net/socket.c:copy_msghdr_from_user
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81815a50-ffffffff81815a7f: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8185ab90)
Location: lib/iov_iter.c:1340
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - mm/madvise.c:__do_sys_process_madvise
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - net/socket.c:copy_msghdr_from_user
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff8185ab90-ffffffff8185abbf: import_iovec (STB_GLOBAL)
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
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d9a8)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffff80001062d9a8-ffff80001062da70: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d45dc)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/io_uring.c:io_import_iovec
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
c07d45dc-c07d46a0: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0eb0)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
c0000000007d0eb0-c0000000007d0fac: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d72a)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffe00045d72a-ffffffe00045d7b4: import_iovec (STB_GLOBAL)
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
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c050)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff8151c050-ffffffff8151c140: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c340)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff8150c340-ffffffff8150c430: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815180e0)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff815180e0-ffffffff815181d0: import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t import_iovec(int type, const struct iovec *uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815318d0)
Location: lib/iov_iter.c:1639
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/splice.c:__do_sys_vmsplice
  - fs/aio.c:aio_setup_rw
  - security/keys/keyctl.c:keyctl_instantiate_key_iov
  - block/scsi_ioctl.c:sg_io
  - net/socket.c:copy_msghdr_from_user
```
**Symbols:**

```
ffffffff815318d0-ffffffff815319c0: import_iovec (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iovec *uvec</code>
</li>
<li>
<b>Param added. </b>
<code>struct iovec **iovp</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct iovec *uvector</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iovec **iov</code>
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
