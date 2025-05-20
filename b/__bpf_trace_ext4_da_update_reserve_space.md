# Function: <code>__bpf_trace_ext4_da_update_reserve_space</code>

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
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d3d0)
Location: include/trace/events/ext4.h:1144
Inline: False
```
**Symbols:**

```
ffffffff8137d3d0-ffffffff8137d3df: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395b30)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffffffff81395b30-ffffffff81395b3f: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfa90)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffffffff813bfa90-ffffffff813bfa9f: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8d60)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffffffff813d8d60-ffffffff813d8d6f: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814252c0)
Location: include/trace/events/ext4.h:1190
Inline: True
```
**Symbols:**

```
ffffffff814252c0-ffffffff814252cf: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cc60)
Location: include/trace/events/ext4.h:1201
Inline: True
```
**Symbols:**

```
ffffffff8143cc60-ffffffff8143cc6f: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442b20)
Location: include/trace/events/ext4.h:1201
Inline: True
```
**Symbols:**

```
ffffffff81442b20-ffffffff81442b2f: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814967c0)
Location: include/trace/events/ext4.h:1201
Inline: True
```
**Symbols:**

```
ffffffff814967c0-ffffffff814967cf: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521270)
Location: include/trace/events/ext4.h:1207
Inline: True
```
**Symbols:**

```
ffffffff81521270-ffffffff8152128b: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdc90)
Location: include/trace/events/ext4.h:1209
Inline: True
```
**Symbols:**

```
ffffffff815bdc90-ffffffff815bdcab: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4a10)
Location: include/trace/events/ext4.h:1216
Inline: True
```
**Symbols:**

```
ffffffff815f4a10-ffffffff815f4a2b: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d3c0)
Location: include/trace/events/ext4.h:1213
Inline: True
```
**Symbols:**

```
ffffffff8162d3c0-ffffffff8162d3db: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
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
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac300)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffff8000104ac300-ffff8000104ac31c: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674400)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
c0674400-c0674438: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3e00)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
c0000000005e3e00-c0000000005e3e34: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
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
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1340)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffffffff813d1340-ffffffff813d134f: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1dc0)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffffffff813c1dc0-ffffffff813c1dcf: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce7d0)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffffffff813ce7d0-ffffffff813ce7df: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_da_update_reserve_space(void *__data, struct inode *inode, int used_blocks, int quota_claim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3a20)
Location: include/trace/events/ext4.h:1165
Inline: False
```
**Symbols:**

```
ffffffff813e3a20-ffffffff813e3a2f: __bpf_trace_ext4_da_update_reserve_space (STB_LOCAL)
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
