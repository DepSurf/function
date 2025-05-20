# Function: <code>__bpf_trace_ext4_find_delalloc_range</code>

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
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d630)
Location: include/trace/events/ext4.h:1946
Inline: False
```
**Symbols:**

```
ffffffff8137d630-ffffffff8137d64a: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395da0)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffffffff81395da0-ffffffff81395dba: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfd40)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffffffff813bfd40-ffffffff813bfd5a: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d9010)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffffffff813d9010-ffffffff813d902a: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814254f0)
Location: include/trace/events/ext4.h:1995
Inline: False
```
**Symbols:**

```
ffffffff814254f0-ffffffff8142550a: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cec0)
Location: include/trace/events/ext4.h:2022
Inline: False
```
**Symbols:**

```
ffffffff8143cec0-ffffffff8143ceda: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
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
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac690)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffff8000104ac690-ffff8000104ac6b8: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674c74)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
c0674c74-c0674cd0: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e4550)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
c0000000005e4550-c0000000005e4584: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
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
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d15f0)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffffffff813d15f0-ffffffff813d160a: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c2070)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffffffff813c2070-ffffffff813c208a: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cea80)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffffffff813cea80-ffffffff813cea9a: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_find_delalloc_range(void *__data, struct inode *inode, ext4_lblk_t from, ext4_lblk_t to, int reverse, int found, ext4_lblk_t found_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3cd0)
Location: include/trace/events/ext4.h:1967
Inline: False
```
**Symbols:**

```
ffffffff813e3cd0-ffffffff813e3cea: __bpf_trace_ext4_find_delalloc_range (STB_LOCAL)
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
