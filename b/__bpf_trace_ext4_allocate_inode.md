# Function: <code>__bpf_trace_ext4_allocate_inode</code>

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
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d370)
Location: include/trace/events/ext4.h:159
Inline: False
```
**Symbols:**

```
ffffffff8137d370-ffffffff8137d37d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395ad0)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffffffff81395ad0-ffffffff81395add: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfa30)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffffffff813bfa30-ffffffff813bfa3d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8d00)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffffffff813d8d00-ffffffff813d8d0d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425260)
Location: include/trace/events/ext4.h:180
Inline: True
```
**Symbols:**

```
ffffffff81425260-ffffffff8142526d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cc00)
Location: include/trace/events/ext4.h:191
Inline: True
```
**Symbols:**

```
ffffffff8143cc00-ffffffff8143cc0d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442ac0)
Location: include/trace/events/ext4.h:191
Inline: True
```
**Symbols:**

```
ffffffff81442ac0-ffffffff81442acd: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496760)
Location: include/trace/events/ext4.h:191
Inline: True
```
**Symbols:**

```
ffffffff81496760-ffffffff8149676d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521190)
Location: include/trace/events/ext4.h:202
Inline: True
```
**Symbols:**

```
ffffffff81521190-ffffffff815211a9: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdb40)
Location: include/trace/events/ext4.h:204
Inline: True
```
**Symbols:**

```
ffffffff815bdb40-ffffffff815bdb59: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f48c0)
Location: include/trace/events/ext4.h:218
Inline: True
```
**Symbols:**

```
ffffffff815f48c0-ffffffff815f48d9: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d2a0)
Location: include/trace/events/ext4.h:218
Inline: True
```
**Symbols:**

```
ffffffff8162d2a0-ffffffff8162d2b9: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
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
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac268)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffff8000104ac268-ffff8000104ac280: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c06742a8)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
c06742a8-c06742e0: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3ce0)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
c0000000005e3ce0-c0000000005e3d10: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
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
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d12e0)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffffffff813d12e0-ffffffff813d12ed: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1d60)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffffffff813c1d60-ffffffff813c1d6d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce770)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffffffff813ce770-ffffffff813ce77d: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_allocate_inode(void *__data, struct inode *inode, struct inode *dir, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e39c0)
Location: include/trace/events/ext4.h:160
Inline: False
```
**Symbols:**

```
ffffffff813e39c0-ffffffff813e39cd: __bpf_trace_ext4_allocate_inode (STB_LOCAL)
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
