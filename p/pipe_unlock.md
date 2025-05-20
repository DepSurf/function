# Function: <code>pipe_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812149d0)
Location: fs/pipe.c:77
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_splice_read
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812149d0-ffffffff812149e8: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123bbc4)
Location: fs/pipe.c:78
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/splice.c:splice_to_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_splice_read
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8123b760-ffffffff8123b778: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124e964)
Location: fs/pipe.c:78
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8124e500-ffffffff8124e518: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125a894)
Location: fs/pipe.c:78
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8125a490-ffffffff8125a4a9: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127cc24)
Location: fs/pipe.c:79
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8127c790-ffffffff8127c7a9: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a3bb4)
Location: fs/pipe.c:74
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812a3720-ffffffff812a3738: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b8d04)
Location: fs/pipe.c:74
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812b8870-ffffffff812b8888: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d58f1)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812d53f0-ffffffff812d5408: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e7461)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812e6f60-ffffffff812e6f78: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8131ed16)
Location: fs/pipe.c:78
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8131e7d0-ffffffff8131e7e8: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132a243)
Location: fs/pipe.c:78
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81329d30-ffffffff81329d48: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813301f3)
Location: fs/pipe.c:93
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8132fcf0-ffffffff8132fd08: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137d9b3)
Location: fs/pipe.c:93
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8137d4b0-ffffffff8137d4c8: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813fe053)
Location: fs/pipe.c:94
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff813fd090-ffffffff813fd0b8: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81487c83)
Location: fs/pipe.c:94
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81486c10-ffffffff81486c38: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bcb43)
Location: fs/pipe.c:94
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff814bba00-ffffffff814bba28: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814eeff3)
Location: fs/pipe.c:94
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff814edf90-ffffffff814edfb8: pipe_unlock (STB_GLOBAL)
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
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff80001039015c)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffff80001038f8b8-ffff80001038f8f8: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0576bf4)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
c0576594-c05765bc: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000487ba4)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
c000000000487100-c000000000487140: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe00025fb6c)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffe00025f522-ffffffe00025f55a: pipe_unlock (STB_GLOBAL)
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
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dfa41)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812df540-ffffffff812df558: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d0681)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812d0180-ffffffff812d0198: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dd851)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812dd350-ffffffff812dd368: pipe_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pipe_unlock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ee7d1)
Location: fs/pipe.c:75
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812ee2e0-ffffffff812ee2f8: pipe_unlock (STB_GLOBAL)
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
