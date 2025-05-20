# Function: <code>__bpf_trace_ext4_direct_IO_enter</code>

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
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d4b0)
Location: include/trace/events/ext4.h:1288
Inline: False
```
**Symbols:**

```
ffffffff8137d4b0-ffffffff8137d4be: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395c20)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffffffff81395c20-ffffffff81395c2e: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfbc0)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffffffff813bfbc0-ffffffff813bfbce: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8e90)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffffffff813d8e90-ffffffff813d8e9e: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425360)
Location: include/trace/events/ext4.h:1334
Inline: False
```
**Symbols:**

```
ffffffff81425360-ffffffff8142536e: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cd10)
Location: include/trace/events/ext4.h:1361
Inline: False
```
**Symbols:**

```
ffffffff8143cd10-ffffffff8143cd1e: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
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
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac498)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffff8000104ac498-ffff8000104ac4b0: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c06747c4)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
c06747c4-c0674804: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e41d0)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
c0000000005e41d0-c0000000005e4200: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
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
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1470)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffffffff813d1470-ffffffff813d147e: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1ef0)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffffffff813c1ef0-ffffffff813c1efe: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce900)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffffffff813ce900-ffffffff813ce90e: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_direct_IO_enter(void *__data, struct inode *inode, loff_t offset, long unsigned int len, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3b50)
Location: include/trace/events/ext4.h:1309
Inline: False
```
**Symbols:**

```
ffffffff813e3b50-ffffffff813e3b5e: __bpf_trace_ext4_direct_IO_enter (STB_LOCAL)
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
