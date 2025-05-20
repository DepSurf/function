# Function: <code>__bpf_trace_ext4_mb_release_inode_pa</code>

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
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d3b0)
Location: include/trace/events/ext4.h:657
Inline: False
```
**Symbols:**

```
ffffffff8137d3b0-ffffffff8137d3bd: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395b10)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffffffff81395b10-ffffffff81395b1d: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfa70)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffffffff813bfa70-ffffffff813bfa7d: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8d40)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffffffff813d8d40-ffffffff813d8d4d: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814252a0)
Location: include/trace/events/ext4.h:698
Inline: False
```
**Symbols:**

```
ffffffff814252a0-ffffffff814252ad: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cc40)
Location: include/trace/events/ext4.h:709
Inline: False
```
**Symbols:**

```
ffffffff8143cc40-ffffffff8143cc4d: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442b00)
Location: include/trace/events/ext4.h:709
Inline: False
```
**Symbols:**

```
ffffffff81442b00-ffffffff81442b0d: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814967a0)
Location: include/trace/events/ext4.h:709
Inline: False
```
**Symbols:**

```
ffffffff814967a0-ffffffff814967ad: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521210)
Location: include/trace/events/ext4.h:715
Inline: True
```
**Symbols:**

```
ffffffff81521210-ffffffff81521229: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdc00)
Location: include/trace/events/ext4.h:717
Inline: True
```
**Symbols:**

```
ffffffff815bdc00-ffffffff815bdc19: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4980)
Location: include/trace/events/ext4.h:724
Inline: True
```
**Symbols:**

```
ffffffff815f4980-ffffffff815f4999: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d360)
Location: include/trace/events/ext4.h:724
Inline: True
```
**Symbols:**

```
ffffffff8162d360-ffffffff8162d379: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
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
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac2d0)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffff8000104ac2d0-ffff8000104ac2e8: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674388)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
c0674388-c06743c8: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3da0)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
c0000000005e3da0-c0000000005e3dcc: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
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
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1320)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffffffff813d1320-ffffffff813d132d: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1da0)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffffffff813c1da0-ffffffff813c1dad: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce7b0)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffffffff813ce7b0-ffffffff813ce7bd: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_mb_release_inode_pa(void *__data, struct ext4_prealloc_space *pa, long long unsigned int block, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3a00)
Location: include/trace/events/ext4.h:678
Inline: False
```
**Symbols:**

```
ffffffff813e3a00-ffffffff813e3a0d: __bpf_trace_ext4_mb_release_inode_pa (STB_LOCAL)
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
