# Function: <code>pipe_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812149b0)
Location: fs/pipe.c:68
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812149b0-ffffffff812149c8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123bbdc)
Location: fs/pipe.c:69
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/splice.c:splice_to_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8123b740-ffffffff8123b758: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124e97c)
Location: fs/pipe.c:69
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8124e4e0-ffffffff8124e4f8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125a8ac)
Location: fs/pipe.c:69
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8125a470-ffffffff8125a489: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127cc3c)
Location: fs/pipe.c:70
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8127c770-ffffffff8127c789: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a3bcc)
Location: fs/pipe.c:65
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812a3700-ffffffff812a3718: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b8d1c)
Location: fs/pipe.c:65
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812b8850-ffffffff812b8868: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d590b)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812d53d0-ffffffff812d53e8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e747b)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812e6f40-ffffffff812e6f58: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8131ecee)
Location: fs/pipe.c:69
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8131e7b0-ffffffff8131e7c8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132a20e)
Location: fs/pipe.c:69
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81329d10-ffffffff81329d28: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813301be)
Location: fs/pipe.c:84
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8132fcd0-ffffffff8132fce8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137d97e)
Location: fs/pipe.c:84
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8137d490-ffffffff8137d4a8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813fe01e)
Location: fs/pipe.c:85
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff813fd060-ffffffff813fd088: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81487c4e)
Location: fs/pipe.c:85
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:generic_splice_sendpage
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81486bd0-ffffffff81486bf8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bcb0e)
Location: fs/pipe.c:85
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff814bb9c0-ffffffff814bb9e8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814eefbe)
Location: fs/pipe.c:85
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_filter
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff814edf50-ffffffff814edf78: pipe_lock (STB_GLOBAL)
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
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff800010390174)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffff80001038f878-ffff80001038f8b8: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0576c10)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
c057656c-c0576594: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000487bc8)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
c0000000004870c0-c000000000487100: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe00025fb86)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffe00025f4ea-ffffffe00025f522: pipe_lock (STB_GLOBAL)
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
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dfa5b)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812df520-ffffffff812df538: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d069b)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812d0160-ffffffff812d0178: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dd86b)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812dd330-ffffffff812dd348: pipe_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pipe_lock(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ee7eb)
Location: fs/pipe.c:66
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_write
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff812ee2c0-ffffffff812ee2d8: pipe_lock (STB_GLOBAL)
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
