# Function: <code>__traceiter_dax_pte_fault</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_dax_pte_fault(void *__data, struct inode *inode, struct vm_fault *vmf, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139caa0)
Location: include/trace/events/fs_dax.h:191
Inline: False
```
**Symbols:**

```
ffffffff8139caa0-ffffffff8139caf1: __traceiter_dax_pte_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_dax_pte_fault(void *__data, struct inode *inode, struct vm_fault *vmf, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a3d50)
Location: include/trace/events/fs_dax.h:191
Inline: False
```
**Symbols:**

```
ffffffff813a3d50-ffffffff813a3d9f: __traceiter_dax_pte_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_dax_pte_fault(void *__data, struct inode *inode, struct vm_fault *vmf, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f3670)
Location: include/trace/events/fs_dax.h:191
Inline: False
```
**Symbols:**

```
ffffffff813f3670-ffffffff813f36bf: __traceiter_dax_pte_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_dax_pte_fault(void *__data, struct inode *inode, struct vm_fault *vmf, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81465d80)
Location: include/trace/events/fs_dax.h:191
Inline: False
```
**Symbols:**

```
ffffffff81465d80-ffffffff81465ddb: __traceiter_dax_pte_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_dax_pte_fault(void *__data, struct inode *inode, struct vm_fault *vmf, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f5e60)
Location: include/trace/events/fs_dax.h:191
Inline: False
```
**Symbols:**

```
ffffffff814f5e60-ffffffff814f5ebb: __traceiter_dax_pte_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_dax_pte_fault(void *__data, struct inode *inode, struct vm_fault *vmf, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152cc50)
Location: include/trace/events/fs_dax.h:191
Inline: False
```
**Symbols:**

```
ffffffff8152cc50-ffffffff8152ccab: __traceiter_dax_pte_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_dax_pte_fault(void *__data, struct inode *inode, struct vm_fault *vmf, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81561b30)
Location: include/trace/events/fs_dax.h:191
Inline: False
```
**Symbols:**

```
ffffffff81561b30-ffffffff81561b8b: __traceiter_dax_pte_fault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
