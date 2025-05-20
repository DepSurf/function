# Function: <code>__bpf_trace_ext4_remove_blocks</code>

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
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, long long int partial_cluster);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d600)
Location: include/trace/events/ext4.h:2037
Inline: False
```
**Symbols:**

```
ffffffff8137d600-ffffffff8137d60d: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395d70)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffffffff81395d70-ffffffff81395d7d: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfd10)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffffffff813bfd10-ffffffff813bfd1d: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8fe0)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffffffff813d8fe0-ffffffff813d8fed: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814254c0)
Location: include/trace/events/ext4.h:2086
Inline: False
```
**Symbols:**

```
ffffffff814254c0-ffffffff814254cd: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143ce70)
Location: include/trace/events/ext4.h:2113
Inline: False
```
**Symbols:**

```
ffffffff8143ce70-ffffffff8143ce7d: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442ce0)
Location: include/trace/events/ext4.h:1937
Inline: False
```
**Symbols:**

```
ffffffff81442ce0-ffffffff81442ced: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496980)
Location: include/trace/events/ext4.h:1937
Inline: False
```
**Symbols:**

```
ffffffff81496980-ffffffff8149698d: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521600)
Location: include/trace/events/ext4.h:1943
Inline: False
```
**Symbols:**

```
ffffffff81521600-ffffffff8152161f: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815be170)
Location: include/trace/events/ext4.h:1980
Inline: False
```
**Symbols:**

```
ffffffff815be170-ffffffff815be18f: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4ef0)
Location: include/trace/events/ext4.h:1987
Inline: False
```
**Symbols:**

```
ffffffff815f4ef0-ffffffff815f4f0f: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d8d0)
Location: include/trace/events/ext4.h:1984
Inline: False
```
**Symbols:**

```
ffffffff8162d8d0-ffffffff8162d8ef: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
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
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac658)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffff8000104ac658-ffff8000104ac670: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674bd8)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
c0674bd8-c0674c24: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e44e0)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
c0000000005e44e0-c0000000005e450c: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
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
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d15c0)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffffffff813d15c0-ffffffff813d15cd: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c2040)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffffffff813c2040-ffffffff813c204d: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cea50)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffffffff813cea50-ffffffff813cea5d: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3ca0)
Location: include/trace/events/ext4.h:2058
Inline: False
```
**Symbols:**

```
ffffffff813e3ca0-ffffffff813e3cad: __bpf_trace_ext4_remove_blocks (STB_LOCAL)
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
