# Function: <code>__bpf_trace_ext4_direct_IO_exit</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d5d0)
Location: include/trace/events/ext4.h:1315
Inline: False
```
**Symbols:**

```
ffffffff8137d5d0-ffffffff8137d5e1: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395d40)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffffffff81395d40-ffffffff81395d51: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfce0)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffffffff813bfce0-ffffffff813bfcf1: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8fb0)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffffffff813d8fb0-ffffffff813d8fc1: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425470)
Location: include/trace/events/ext4.h:1361
Inline: False
```
**Symbols:**

```
ffffffff81425470-ffffffff81425481: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143ce20)
Location: include/trace/events/ext4.h:1388
Inline: False
```
**Symbols:**

```
ffffffff8143ce20-ffffffff8143ce31: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
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
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac618)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffff8000104ac618-ffff8000104ac634: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674b34)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
c0674b34-c0674b8c: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e4470)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
c0000000005e4470-c0000000005e44a4: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
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
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1590)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffffffff813d1590-ffffffff813d15a1: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c2010)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffffffff813c2010-ffffffff813c2021: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cea20)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffffffff813cea20-ffffffff813cea31: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_exit(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3c70)
Location: include/trace/events/ext4.h:1336
Inline: False
```
**Symbols:**

```
ffffffff813e3c70-ffffffff813e3c81: __bpf_trace_ext4_direct_IO_exit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
