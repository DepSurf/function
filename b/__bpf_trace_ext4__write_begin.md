# Function: <code>__bpf_trace_ext4__write_begin</code>

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
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d480)
Location: include/trace/events/ext4.h:273
Inline: True
```
**Symbols:**

```
ffffffff8137d480-ffffffff8137d490: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395bf0)
Location: include/trace/events/ext4.h:294
Inline: True
```
**Symbols:**

```
ffffffff81395bf0-ffffffff81395c00: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfb80)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
ffffffff813bfb80-ffffffff813bfb90: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8e50)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
ffffffff813d8e50-ffffffff813d8e60: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425330)
Location: include/trace/events/ext4.h:314
Inline: True
```
**Symbols:**

```
ffffffff81425330-ffffffff81425340: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cce0)
Location: include/trace/events/ext4.h:325
Inline: True
```
**Symbols:**

```
ffffffff8143cce0-ffffffff8143ccf0: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442b90)
Location: include/trace/events/ext4.h:325
Inline: True
```
**Symbols:**

```
ffffffff81442b90-ffffffff81442ba0: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496830)
Location: include/trace/events/ext4.h:325
Inline: True
```
**Symbols:**

```
ffffffff81496830-ffffffff81496840: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815211b0)
Location: include/trace/events/ext4.h:336
Inline: False
```
**Symbols:**

```
ffffffff815211b0-ffffffff815211c9: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdb70)
Location: include/trace/events/ext4.h:338
Inline: False
```
**Symbols:**

```
ffffffff815bdb70-ffffffff815bdb89: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f48f0)
Location: include/trace/events/ext4.h:352
Inline: False
```
**Symbols:**

```
ffffffff815f48f0-ffffffff815f4909: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d2d0)
Location: include/trace/events/ext4.h:352
Inline: False
```
**Symbols:**

```
ffffffff8162d2d0-ffffffff8162d2e9: __bpf_trace_ext4__write_begin (STB_LOCAL)
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
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac440)
Location: include/trace/events/ext4.h:294
Inline: True
```
**Symbols:**

```
ffff8000104ac440-ffff8000104ac45c: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c06746e8)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
c06746e8-c0674728: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e4100)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
c0000000005e4100-c0000000005e412c: __bpf_trace_ext4__write_begin (STB_LOCAL)
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
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1430)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
ffffffff813d1430-ffffffff813d1440: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1eb0)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
ffffffff813c1eb0-ffffffff813c1ec0: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce8c0)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
ffffffff813ce8c0-ffffffff813ce8d0: __bpf_trace_ext4__write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4__write_begin(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3b10)
Location: include/trace/events/ext4.h:294
Inline: False
```
**Symbols:**

```
ffffffff813e3b10-ffffffff813e3b20: __bpf_trace_ext4__write_begin (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
