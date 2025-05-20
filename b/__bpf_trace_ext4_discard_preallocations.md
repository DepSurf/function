# Function: <code>__bpf_trace_ext4_discard_preallocations</code>

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
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:707
Inline: False
```
**Symbols:**

```
ffffffff8137e820-ffffffff8137e82b: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffffffff81397070-ffffffff8139707b: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bf9b0)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffffffff813bf9b0-ffffffff813bf9bb: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8c80)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffffffff813d8c80-ffffffff813d8c8b: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len, unsigned int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:748
Inline: False
```
**Symbols:**

```
ffffffff814264e0-ffffffff814264ef: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len, unsigned int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:759
Inline: False
```
**Symbols:**

```
ffffffff8143dbd0-ffffffff8143dbdf: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len, unsigned int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:759
Inline: False
```
**Symbols:**

```
ffffffff814439d0-ffffffff814439df: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len, unsigned int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:759
Inline: False
```
**Symbols:**

```
ffffffff814977b0-ffffffff814977bf: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len, unsigned int needed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521230)
Location: include/trace/events/ext4.h:765
Inline: True
```
**Symbols:**

```
ffffffff81521230-ffffffff8152124b: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len, unsigned int needed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdc30)
Location: include/trace/events/ext4.h:767
Inline: True
```
**Symbols:**

```
ffffffff815bdc30-ffffffff815bdc4b: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len, unsigned int needed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f49b0)
Location: include/trace/events/ext4.h:774
Inline: True
```
**Symbols:**

```
ffffffff815f49b0-ffffffff815f49cb: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d240)
Location: include/trace/events/ext4.h:774
Inline: True
```
**Symbols:**

```
ffffffff8162d240-ffffffff8162d257: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
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
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffff8000104ada98-ffff8000104adaac: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
c06741c4-c06741dc: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3b60)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
c0000000005e3b60-c0000000005e3b8c: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
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
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1260)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffffffff813d1260-ffffffff813d126b: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1ce0)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffffffff813c1ce0-ffffffff813c1ceb: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce6f0)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffffffff813ce6f0-ffffffff813ce6fb: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_discard_preallocations(void *__data, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3940)
Location: include/trace/events/ext4.h:728
Inline: False
```
**Symbols:**

```
ffffffff813e3940-ffffffff813e394b: __bpf_trace_ext4_discard_preallocations (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int len</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int needed</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int needed</code>
</li>
</ul>
</details>
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
