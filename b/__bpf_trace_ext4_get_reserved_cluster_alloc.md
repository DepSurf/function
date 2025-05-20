# Function: <code>__bpf_trace_ext4_get_reserved_cluster_alloc</code>

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
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d430)
Location: include/trace/events/ext4.h:1981
Inline: True
```
**Symbols:**

```
ffffffff8137d430-ffffffff8137d43f: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395b90)
Location: include/trace/events/ext4.h:2002
Inline: True
```
**Symbols:**

```
ffffffff81395b90-ffffffff81395b9f: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfaf0)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
ffffffff813bfaf0-ffffffff813bfaff: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8dc0)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
ffffffff813d8dc0-ffffffff813d8dcf: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2030
Inline: False
```
**Symbols:**

```
ffffffff81426610-ffffffff8142661f: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2057
Inline: False
```
**Symbols:**

```
ffffffff8143dd00-ffffffff8143dd0f: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac3a0)
Location: include/trace/events/ext4.h:2002
Inline: True
```
**Symbols:**

```
ffff8000104ac3a0-ffff8000104ac3bc: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674550)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
c0674550-c0674588: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3f30)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
c0000000005e3f30-c0000000005e3f5c: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
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
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d13a0)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
ffffffff813d13a0-ffffffff813d13af: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1e20)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
ffffffff813c1e20-ffffffff813c1e2f: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce830)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
ffffffff813ce830-ffffffff813ce83f: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_get_reserved_cluster_alloc(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3a80)
Location: include/trace/events/ext4.h:2002
Inline: False
```
**Symbols:**

```
ffffffff813e3a80-ffffffff813e3a8f: __bpf_trace_ext4_get_reserved_cluster_alloc (STB_LOCAL)
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
