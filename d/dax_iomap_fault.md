# Function: <code>dax_iomap_fault</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dax_iomap_fault(struct vm_area_struct *vma, struct vm_fault *vmf, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129c1a0)
Location: fs/dax.c:1125
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff8129c1a0-ffffffff8129c8ec: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812aae60)
Location: fs/dax.c:1455
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff812aae60-ffffffff812abf2c: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812ce690)
Location: fs/dax.c:1498
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff812ce690-ffffffff812cf79e: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f8c90)
Location: fs/dax.c:1721
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff812f8c90-ffffffff812f9de5: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130e610)
Location: fs/dax.c:1626
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff8130e610-ffffffff8130e654: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813365b0)
Location: fs/dax.c:1642
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff813365b0-ffffffff813365f2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8134a1b0)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff8134a1b0-ffffffff8134a1f2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138f9a0)
Location: fs/dax.c:1636
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff8138f9a0-ffffffff8138f9d7: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a0f70)
Location: fs/dax.c:1651
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff813a0f70-ffffffff813a0fa7: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a8100)
Location: fs/dax.c:1663
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff813a8100-ffffffff813a8135: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f7840)
Location: fs/dax.c:1635
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff813f7840-ffffffff813f7875: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8146a660)
Location: fs/dax.c:1595
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff8146a660-ffffffff8146a6c2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fb120)
Location: fs/dax.c:1879
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff814fb120-ffffffff814fb182: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81532570)
Location: fs/dax.c:1921
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff81532570-ffffffff815325d2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, unsigned int order, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81567460)
Location: fs/dax.c:1907
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff81567460-ffffffff815674ce: dax_iomap_fault (STB_GLOBAL)
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
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff80001040a528)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffff80001040a528-ffff80001040a58c: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000516fb0)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
c000000000516fb0-c000000000516ffc: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b4034)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffe0002b4034-ffffffe0002b408c: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81342790)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81342790-ffffffff813427d2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81333480)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81333480-ffffffff813334c2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81340260)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81340260-ffffffff813402a2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81353560)
Location: fs/dax.c:1646
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81353560-ffffffff813535a2: dax_iomap_fault (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum page_entry_size pe_size</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, vmf, ops</code> ➡️ <code>vmf, pe_size, ops</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops *ops</code> ➡️ <code>const struct iomap_ops *ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pfn_t *pfnp</code>
</li>
<li>
<b>Param reordered. </b>
<code>vmf, pe_size, ops</code> ➡️ <code>vmf, pe_size, pfnp, ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *iomap_errp</code>
</li>
<li>
<b>Param reordered. </b>
<code>vmf, pe_size, pfnp, ops</code> ➡️ <code>vmf, pe_size, pfnp, iomap_errp, ops</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
