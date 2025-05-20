# Function: <code>__io_fixed_fd_install</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_fixed_fd_install(struct io_ring_ctx *ctx, struct file *file, unsigned int file_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff817941b0)
Location: io_uring/filetable.c:107
Inline: False
Direct callers:
  - io_uring/filetable.c:io_fixed_fd_install
  - io_uring/filetable.c:io_fixed_fd_install
  - io_uring/msg_ring.c:io_msg_install_complete
```
**Symbols:**

```
ffffffff817941b0-ffffffff81794248: __io_fixed_fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_fixed_fd_install(struct io_ring_ctx *ctx, struct file *file, unsigned int file_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff817d4e90)
Location: io_uring/filetable.c:99
Inline: False
Direct callers:
  - io_uring/filetable.c:io_fixed_fd_install
  - io_uring/filetable.c:io_fixed_fd_install
  - io_uring/msg_ring.c:io_msg_install_complete
```
**Symbols:**

```
ffffffff817d4e90-ffffffff817d4f37: __io_fixed_fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __io_fixed_fd_install(struct io_ring_ctx *ctx, struct file *file, unsigned int file_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff81818ce0)
Location: io_uring/filetable.c:96
Inline: False
Direct callers:
  - io_uring/filetable.c:io_fixed_fd_install
  - io_uring/filetable.c:io_fixed_fd_install
  - io_uring/msg_ring.c:io_msg_install_complete
```
**Symbols:**

```
ffffffff81818ce0-ffffffff81818d87: __io_fixed_fd_install (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
