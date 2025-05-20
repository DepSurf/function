# Function: <code>dax_iomap_pte_fault</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812aaff3)
Location: fs/dax.c:1075
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
In fs/dax.c (ffffffff812ce85d)
Location: fs/dax.c:1098
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
In fs/dax.c (ffffffff812f8e8d)
Location: fs/dax.c:1335
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
In fs/dax.c (ffffffff8130d330)
Location: fs/dax.c:1238
Inline: True
```
**Symbols:**

```
ffffffff8130d330-ffffffff8130dc4e: dax_iomap_pte_fault.isra.40 (STB_LOCAL)
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
In fs/dax.c (ffffffff81335530)
Location: fs/dax.c:1241
Inline: True
```
**Symbols:**

```
ffffffff81335530-ffffffff81335e6f: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
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
In fs/dax.c (ffffffff81349130)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
ffffffff81349130-ffffffff81349a6f: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138e4b0)
Location: fs/dax.c:1232
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8138e4b0-ffffffff8138ec52: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139fc00)
Location: fs/dax.c:1247
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8139fc00-ffffffff813a0349: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a71d0)
Location: fs/dax.c:1259
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff813a71d0-ffffffff813a7a37: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f7090)
Location: fs/dax.c:1424
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff813f7090-ffffffff813f740d: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81469dd0)
Location: fs/dax.c:1384
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff81469dd0-ffffffff8146a1d7: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fa870)
Location: fs/dax.c:1668
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff814fa870-ffffffff814fac74: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81531cc0)
Location: fs/dax.c:1711
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff81531cc0-ffffffff815320d0: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault *vmf, pfn_t *pfnp, int *iomap_errp, const struct iomap_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81566bb0)
Location: fs/dax.c:1697
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff81566bb0-ffffffff81566fc0: dax_iomap_pte_fault (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffff800010409a18)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
ffff800010409a18-ffff80001040a524: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
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
In fs/dax.c (c000000000515ca0)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
c000000000515ca0-c000000000516688: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffe0002b36ce)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
ffffffe0002b36ce-ffffffe0002b4034: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
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
In fs/dax.c (ffffffff81341710)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
ffffffff81341710-ffffffff8134204f: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
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
In fs/dax.c (ffffffff813320c0)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
ffffffff813320c0-ffffffff81332a43: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
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
In fs/dax.c (ffffffff8133f1e0)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
ffffffff8133f1e0-ffffffff8133fb1f: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
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
In fs/dax.c (ffffffff81352b60)
Location: fs/dax.c:1245
Inline: True
```
**Symbols:**

```
ffffffff81352b60-ffffffff8135355c: dax_iomap_pte_fault.isra.0 (STB_LOCAL)
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
