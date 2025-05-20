# Function: <code>__bpf_trace_ext4_es_find_extent_range_enter</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395a70)
Location: include/trace/events/ext4.h:2313
Inline: True
```
**Symbols:**

```
ffffffff81395a70-ffffffff81395a7d: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bf920)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
ffffffff813bf920-ffffffff813bf92d: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8bf0)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
ffffffff813d8bf0-ffffffff813d8bfd: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425240)
Location: include/trace/events/ext4.h:2341
Inline: True
```
**Symbols:**

```
ffffffff81425240-ffffffff8142524d: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cbe0)
Location: include/trace/events/ext4.h:2368
Inline: True
```
**Symbols:**

```
ffffffff8143cbe0-ffffffff8143cbed: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442aa0)
Location: include/trace/events/ext4.h:2192
Inline: True
```
**Symbols:**

```
ffffffff81442aa0-ffffffff81442aad: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496740)
Location: include/trace/events/ext4.h:2192
Inline: True
```
**Symbols:**

```
ffffffff81496740-ffffffff8149674d: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521150)
Location: include/trace/events/ext4.h:2198
Inline: True
```
**Symbols:**

```
ffffffff81521150-ffffffff81521167: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdae0)
Location: include/trace/events/ext4.h:2235
Inline: True
```
**Symbols:**

```
ffffffff815bdae0-ffffffff815bdaf7: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4860)
Location: include/trace/events/ext4.h:2242
Inline: True
```
**Symbols:**

```
ffffffff815f4860-ffffffff815f4877: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2239
Inline: False
```
**Symbols:**

```
ffffffff8162ff90-ffffffff8162ffa7: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
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
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac1d8)
Location: include/trace/events/ext4.h:2313
Inline: True
```
**Symbols:**

```
ffff8000104ac1d8-ffff8000104ac1f0: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674110)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
c0674110-c0674138: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e39b0)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
c0000000005e39b0-c0000000005e39dc: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
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
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d11d0)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
ffffffff813d11d0-ffffffff813d11dd: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1c50)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
ffffffff813c1c50-ffffffff813c1c5d: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce660)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
ffffffff813ce660-ffffffff813ce66d: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void *__data, struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e38b0)
Location: include/trace/events/ext4.h:2313
Inline: False
```
**Symbols:**

```
ffffffff813e38b0-ffffffff813e38bd: __bpf_trace_ext4_es_find_extent_range_enter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
