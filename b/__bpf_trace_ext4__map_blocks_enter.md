# Function: <code>__bpf_trace_ext4__map_blocks_enter</code>

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
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d4f0)
Location: include/trace/events/ext4.h:1589
Inline: False
```
**Symbols:**

```
ffffffff8137d4f0-ffffffff8137d502: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395c60)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffffffff81395c60-ffffffff81395c72: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfc00)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffffffff813bfc00-ffffffff813bfc12: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8ed0)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffffffff813d8ed0-ffffffff813d8ee2: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814253a0)
Location: include/trace/events/ext4.h:1635
Inline: False
```
**Symbols:**

```
ffffffff814253a0-ffffffff814253b2: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cd50)
Location: include/trace/events/ext4.h:1662
Inline: True
```
**Symbols:**

```
ffffffff8143cd50-ffffffff8143cd62: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442bf0)
Location: include/trace/events/ext4.h:1604
Inline: True
```
**Symbols:**

```
ffffffff81442bf0-ffffffff81442c02: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496890)
Location: include/trace/events/ext4.h:1604
Inline: True
```
**Symbols:**

```
ffffffff81496890-ffffffff814968a2: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521430)
Location: include/trace/events/ext4.h:1610
Inline: True
```
**Symbols:**

```
ffffffff81521430-ffffffff81521451: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdf30)
Location: include/trace/events/ext4.h:1612
Inline: True
```
**Symbols:**

```
ffffffff815bdf30-ffffffff815bdf51: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4cb0)
Location: include/trace/events/ext4.h:1619
Inline: True
```
**Symbols:**

```
ffffffff815f4cb0-ffffffff815f4cd1: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d690)
Location: include/trace/events/ext4.h:1616
Inline: True
```
**Symbols:**

```
ffffffff8162d690-ffffffff8162d6b1: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
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
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac500)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffff8000104ac500-ffff8000104ac520: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c06748cc)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
c06748cc-c0674910: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e4290)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
c0000000005e4290-c0000000005e42bc: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
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
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d14b0)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffffffff813d14b0-ffffffff813d14c2: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1f30)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffffffff813c1f30-ffffffff813c1f42: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce940)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffffffff813ce940-ffffffff813ce952: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4__map_blocks_enter(void *__data, struct inode *inode, ext4_lblk_t lblk, unsigned int len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3b90)
Location: include/trace/events/ext4.h:1610
Inline: False
```
**Symbols:**

```
ffffffff813e3b90-ffffffff813e3ba2: __bpf_trace_ext4__map_blocks_enter (STB_LOCAL)
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
