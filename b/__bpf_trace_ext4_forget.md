# Function: <code>__bpf_trace_ext4_forget</code>

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
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d3c0)
Location: include/trace/events/ext4.h:1117
Inline: False
```
**Symbols:**

```
ffffffff8137d3c0-ffffffff8137d3cd: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395b20)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffffffff81395b20-ffffffff81395b2d: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfa80)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffffffff813bfa80-ffffffff813bfa8d: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8d50)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffffffff813d8d50-ffffffff813d8d5d: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814252b0)
Location: include/trace/events/ext4.h:1163
Inline: True
```
**Symbols:**

```
ffffffff814252b0-ffffffff814252bd: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cc50)
Location: include/trace/events/ext4.h:1174
Inline: True
```
**Symbols:**

```
ffffffff8143cc50-ffffffff8143cc5d: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442b10)
Location: include/trace/events/ext4.h:1174
Inline: True
```
**Symbols:**

```
ffffffff81442b10-ffffffff81442b1d: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814967b0)
Location: include/trace/events/ext4.h:1174
Inline: True
```
**Symbols:**

```
ffffffff814967b0-ffffffff814967bd: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521250)
Location: include/trace/events/ext4.h:1180
Inline: True
```
**Symbols:**

```
ffffffff81521250-ffffffff81521269: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdc60)
Location: include/trace/events/ext4.h:1182
Inline: True
```
**Symbols:**

```
ffffffff815bdc60-ffffffff815bdc79: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f49e0)
Location: include/trace/events/ext4.h:1189
Inline: True
```
**Symbols:**

```
ffffffff815f49e0-ffffffff815f49f9: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d390)
Location: include/trace/events/ext4.h:1186
Inline: True
```
**Symbols:**

```
ffffffff8162d390-ffffffff8162d3a9: __bpf_trace_ext4_forget (STB_LOCAL)
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
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac2e8)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffff8000104ac2e8-ffff8000104ac300: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c06743c8)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
c06743c8-c0674400: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3dd0)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
c0000000005e3dd0-c0000000005e3e00: __bpf_trace_ext4_forget (STB_LOCAL)
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
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1330)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffffffff813d1330-ffffffff813d133d: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1db0)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffffffff813c1db0-ffffffff813c1dbd: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce7c0)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffffffff813ce7c0-ffffffff813ce7cd: __bpf_trace_ext4_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_forget(void *__data, struct inode *inode, int is_metadata, __u64 block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3a10)
Location: include/trace/events/ext4.h:1138
Inline: False
```
**Symbols:**

```
ffffffff813e3a10-ffffffff813e3a1d: __bpf_trace_ext4_forget (STB_LOCAL)
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
