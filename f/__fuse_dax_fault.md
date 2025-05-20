# Function: <code>__fuse_dax_fault</code>

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
vm_fault_t __fuse_dax_fault(struct vm_fault *vmf, enum page_entry_size pe_size, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149c480)
Location: fs/fuse/dax.c:791
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_huge_fault
  - fs/fuse/dax.c:fuse_dax_fault
```
**Symbols:**

```
ffffffff8149c480-ffffffff8149c66d: __fuse_dax_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault *vmf, enum page_entry_size pe_size, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a24b0)
Location: fs/fuse/dax.c:791
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_huge_fault
  - fs/fuse/dax.c:fuse_dax_fault
```
**Symbols:**

```
ffffffff814a24b0-ffffffff814a269d: __fuse_dax_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault *vmf, enum page_entry_size pe_size, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fa550)
Location: fs/fuse/dax.c:790
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_huge_fault
  - fs/fuse/dax.c:fuse_dax_fault
```
**Symbols:**

```
ffffffff814fa550-ffffffff814fa748: __fuse_dax_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault *vmf, enum page_entry_size pe_size, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158aa40)
Location: fs/fuse/dax.c:787
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_huge_fault
  - fs/fuse/dax.c:fuse_dax_fault
```
**Symbols:**

```
ffffffff8158aa40-ffffffff8158ac93: __fuse_dax_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault *vmf, enum page_entry_size pe_size, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816311a0)
Location: fs/fuse/dax.c:787
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_huge_fault
  - fs/fuse/dax.c:fuse_dax_fault
```
**Symbols:**

```
ffffffff816311a0-ffffffff816313f0: __fuse_dax_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault *vmf, enum page_entry_size pe_size, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816693d0)
Location: fs/fuse/dax.c:787
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_huge_fault
  - fs/fuse/dax.c:fuse_dax_fault
```
**Symbols:**

```
ffffffff816693d0-ffffffff81669626: __fuse_dax_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault *vmf, unsigned int order, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a36d0)
Location: fs/fuse/dax.c:787
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_huge_fault
  - fs/fuse/dax.c:fuse_dax_fault
```
**Symbols:**

```
ffffffff816a36d0-ffffffff816a3926: __fuse_dax_fault (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_entry_size pe_size</code>
</li>
</ul>
</details>
</li>
</ul>
