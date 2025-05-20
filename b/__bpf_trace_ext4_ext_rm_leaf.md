# Function: <code>__bpf_trace_ext4_ext_rm_leaf</code>

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
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, long long int partial_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d580)
Location: include/trace/events/ext4.h:2078
Inline: False
```
**Symbols:**

```
ffffffff8137d580-ffffffff8137d58d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395cf0)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffffffff81395cf0-ffffffff81395cfd: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfc90)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffffffff813bfc90-ffffffff813bfc9d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8f60)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffffffff813d8f60-ffffffff813d8f6d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425420)
Location: include/trace/events/ext4.h:2133
Inline: False
```
**Symbols:**

```
ffffffff81425420-ffffffff8142542d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cdd0)
Location: include/trace/events/ext4.h:2160
Inline: False
```
**Symbols:**

```
ffffffff8143cdd0-ffffffff8143cddd: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442c60)
Location: include/trace/events/ext4.h:1984
Inline: False
```
**Symbols:**

```
ffffffff81442c60-ffffffff81442c6d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496900)
Location: include/trace/events/ext4.h:1984
Inline: False
```
**Symbols:**

```
ffffffff81496900-ffffffff8149690d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815214d0)
Location: include/trace/events/ext4.h:1990
Inline: False
```
**Symbols:**

```
ffffffff815214d0-ffffffff815214ec: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815be010)
Location: include/trace/events/ext4.h:2027
Inline: False
```
**Symbols:**

```
ffffffff815be010-ffffffff815be02c: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4d90)
Location: include/trace/events/ext4.h:2034
Inline: False
```
**Symbols:**

```
ffffffff815f4d90-ffffffff815f4dac: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d770)
Location: include/trace/events/ext4.h:2031
Inline: False
```
**Symbols:**

```
ffffffff8162d770-ffffffff8162d78c: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
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
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac5c0)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffff8000104ac5c0-ffff8000104ac5d8: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674a60)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
c0674a60-c0674aa4: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e43d0)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
c0000000005e43d0-c0000000005e43fc: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
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
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1540)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffffffff813d1540-ffffffff813d154d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1fc0)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffffffff813c1fc0-ffffffff813c1fcd: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce9d0)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffffffff813ce9d0-ffffffff813ce9dd: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_ext_rm_leaf(void *__data, struct inode *inode, ext4_lblk_t start, struct ext4_extent *ex, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3c20)
Location: include/trace/events/ext4.h:2105
Inline: False
```
**Symbols:**

```
ffffffff813e3c20-ffffffff813e3c2d: __bpf_trace_ext4_ext_rm_leaf (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct partial_cluster *pc</code>
</li>
<li>
<b>Param removed. </b>
<code>long long int partial_cluster</code>
</li>
</ul>
</details>
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
