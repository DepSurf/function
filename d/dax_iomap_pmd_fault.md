# Function: <code>dax_iomap_pmd_fault</code>

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
int dax_iomap_pmd_fault(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129c8f0)
Location: fs/dax.c:1324
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_pmd_fault
```
**Symbols:**

```
ffffffff8129c8f0-ffffffff8129d06e: dax_iomap_pmd_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812aaea0)
Location: fs/dax.c:1306
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812ce6d7)
Location: fs/dax.c:1317
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f8cdd)
Location: fs/dax.c:1542
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff8130dc50)
Location: fs/dax.c:1445
Inline: True
```
**Symbols:**

```
ffffffff8130dc50-ffffffff8130e60a: dax_iomap_pmd_fault.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff81335e70)
Location: fs/dax.c:1462
Inline: True
```
**Symbols:**

```
ffffffff81335e70-ffffffff813365ae: dax_iomap_pmd_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff81349a70)
Location: fs/dax.c:1466
Inline: True
```
**Symbols:**

```
ffffffff81349a70-ffffffff8134a1ae: dax_iomap_pmd_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138f1e0)
Location: fs/dax.c:1454
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8138f1e0-ffffffff8138f996: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a0870)
Location: fs/dax.c:1469
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff813a0870-ffffffff813a0f68: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a7a40)
Location: fs/dax.c:1481
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff813a7a40-ffffffff813a80fb: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f7410)
Location: fs/dax.c:1534
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff813f7410-ffffffff813f7838: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8146a1e0)
Location: fs/dax.c:1494
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8146a1e0-ffffffff8146a65a: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fac90)
Location: fs/dax.c:1778
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff814fac90-ffffffff814fb10a: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815320e0)
Location: fs/dax.c:1821
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff815320e0-ffffffff8153255d: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault *vmf, pfn_t *pfnp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81566fd0)
Location: fs/dax.c:1807
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff81566fd0-ffffffff8156744d: dax_iomap_pmd_fault (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1626
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (c000000000516690)
Location: fs/dax.c:1466
Inline: True
```
**Symbols:**

```
c000000000516690-c000000000516fac: dax_iomap_pmd_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1626
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff81342050)
Location: fs/dax.c:1466
Inline: True
```
**Symbols:**

```
ffffffff81342050-ffffffff8134278e: dax_iomap_pmd_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff81332a50)
Location: fs/dax.c:1466
Inline: True
```
**Symbols:**

```
ffffffff81332a50-ffffffff81333472: dax_iomap_pmd_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff8133fb20)
Location: fs/dax.c:1466
Inline: True
```
**Symbols:**

```
ffffffff8133fb20-ffffffff8134025e: dax_iomap_pmd_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff813520f0)
Location: fs/dax.c:1466
Inline: True
```
**Symbols:**

```
ffffffff813520f0-ffffffff81352b51: dax_iomap_pmd_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
