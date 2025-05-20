# Function: <code>__bpf_trace_ext4__fallocate_mode</code>

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
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d4c0)
Location: include/trace/events/ext4.h:1346
Inline: False
```
**Symbols:**

```
ffffffff8137d4c0-ffffffff8137d4ce: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395c30)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff81395c30-ffffffff81395c3e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfbd0)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff813bfbd0-ffffffff813bfbde: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8ea0)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff813d8ea0-ffffffff813d8eae: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425370)
Location: include/trace/events/ext4.h:1392
Inline: False
```
**Symbols:**

```
ffffffff81425370-ffffffff8142537e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cd20)
Location: include/trace/events/ext4.h:1419
Inline: True
```
**Symbols:**

```
ffffffff8143cd20-ffffffff8143cd2e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442bc0)
Location: include/trace/events/ext4.h:1361
Inline: True
```
**Symbols:**

```
ffffffff81442bc0-ffffffff81442bce: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496860)
Location: include/trace/events/ext4.h:1361
Inline: True
```
**Symbols:**

```
ffffffff81496860-ffffffff8149686e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815213d0)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff815213d0-ffffffff815213ed: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdea0)
Location: include/trace/events/ext4.h:1369
Inline: False
```
**Symbols:**

```
ffffffff815bdea0-ffffffff815bdebd: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4c20)
Location: include/trace/events/ext4.h:1376
Inline: False
```
**Symbols:**

```
ffffffff815f4c20-ffffffff815f4c3d: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d600)
Location: include/trace/events/ext4.h:1373
Inline: False
```
**Symbols:**

```
ffffffff8162d600-ffffffff8162d61d: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
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
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac4b0)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffff8000104ac4b0-ffff8000104ac4c8: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674804)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
c0674804-c0674848: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e4200)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
c0000000005e4200-c0000000005e4230: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
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
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1480)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff813d1480-ffffffff813d148e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1f00)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff813c1f00-ffffffff813c1f0e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce910)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff813ce910-ffffffff813ce91e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4__fallocate_mode(void *__data, struct inode *inode, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3b60)
Location: include/trace/events/ext4.h:1367
Inline: False
```
**Symbols:**

```
ffffffff813e3b60-ffffffff813e3b6e: __bpf_trace_ext4__fallocate_mode (STB_LOCAL)
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
