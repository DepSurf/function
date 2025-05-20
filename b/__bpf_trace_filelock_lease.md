# Function: <code>__bpf_trace_filelock_lease</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fd660)
Location: include/trace/events/filelock.h:115
Inline: True
```
**Symbols:**

```
ffffffff812fd660-ffffffff812fd66b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81312ee0)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff81312ee0-ffffffff81312eeb: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133a660)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
ffffffff8133a660-ffffffff8133a66b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81352b90)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
ffffffff81352b90-ffffffff81352b9b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81399550)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff81399550-ffffffff8139955b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ab030)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff813ab030-ffffffff813ab03b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b2500)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff813b2500-ffffffff813b250b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814020f0)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff814020f0-ffffffff814020fb: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814769b0)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff814769b0-ffffffff814769c5: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81509060)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff81509060-ffffffff81509075: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81540620)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff81540620-ffffffff81540635: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81575b00)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffffffff81575b00-ffffffff81575b15: __bpf_trace_filelock_lease (STB_LOCAL)
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
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104146b8)
Location: include/trace/events/filelock.h:119
Inline: True
```
**Symbols:**

```
ffff8000104146b8-ffff8000104146cc: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e0df4)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
c05e0df4-c05e0e1c: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005235c0)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
c0000000005235c0-c0000000005235ec: __bpf_trace_filelock_lease (STB_LOCAL)
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
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b170)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
ffffffff8134b170-ffffffff8134b17b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133be50)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
ffffffff8133be50-ffffffff8133be5b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81348c40)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
ffffffff81348c40-ffffffff81348c4b: __bpf_trace_filelock_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135bf80)
Location: include/trace/events/filelock.h:119
Inline: False
```
**Symbols:**

```
ffffffff8135bf80-ffffffff8135bf8b: __bpf_trace_filelock_lease (STB_LOCAL)
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
