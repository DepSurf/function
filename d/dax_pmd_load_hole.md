# Function: <code>dax_pmd_load_hole</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129cd2d)
Location: fs/dax.c:1289
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
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
In fs/dax.c (ffffffff812ab731)
Location: fs/dax.c:1267
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
In fs/dax.c (ffffffff812ceee0)
Location: fs/dax.c:1278
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
In fs/dax.c (ffffffff812f9685)
Location: fs/dax.c:1503
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130e128)
Location: fs/dax.c:1407
Inline: True
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
In fs/dax.c (ffffffff81334610)
Location: fs/dax.c:1410
Inline: True
```
**Symbols:**

```
ffffffff81334610-ffffffff81334874: dax_pmd_load_hole.isra.0 (STB_LOCAL)
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
In fs/dax.c (ffffffff813481e0)
Location: fs/dax.c:1414
Inline: True
```
**Symbols:**

```
ffffffff813481e0-ffffffff81348444: dax_pmd_load_hole.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff8138ec60)
Location: fs/dax.c:1402
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff8138ec60-ffffffff8138eec4: dax_pmd_load_hole.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff813a0350)
Location: fs/dax.c:1417
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff813a0350-ffffffff813a058b: dax_pmd_load_hole.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff813a6a30)
Location: fs/dax.c:1429
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff813a6a30-ffffffff813a6c57: dax_pmd_load_hole.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff813f64c0)
Location: fs/dax.c:1070
Inline: True
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813f64c0-ffffffff813f66e1: dax_pmd_load_hole.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff81468bc0)
Location: fs/dax.c:987
Inline: True
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81468bc0-ffffffff81468e2c: dax_pmd_load_hole.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t dax_pmd_load_hole(struct xa_state *xas, struct vm_fault *vmf, const struct iomap_iter *iter, void **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f9760)
Location: fs/dax.c:1189
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff814f9760-ffffffff814f99c7: dax_pmd_load_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t dax_pmd_load_hole(struct xa_state *xas, struct vm_fault *vmf, const struct iomap_iter *iter, void **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81530be0)
Location: fs/dax.c:1216
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81530be0-ffffffff81530e50: dax_pmd_load_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t dax_pmd_load_hole(struct xa_state *xas, struct vm_fault *vmf, const struct iomap_iter *iter, void **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81565ac0)
Location: fs/dax.c:1202
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81565ac0-ffffffff81565d30: dax_pmd_load_hole (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (c000000000514440)
Location: fs/dax.c:1414
Inline: True
```
**Symbols:**

```
c000000000514440-c000000000514950: dax_pmd_load_hole.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff813407c0)
Location: fs/dax.c:1414
Inline: True
```
**Symbols:**

```
ffffffff813407c0-ffffffff81340a24: dax_pmd_load_hole.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81332efe)
Location: fs/dax.c:1414
Inline: True
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
In fs/dax.c (ffffffff8133e290)
Location: fs/dax.c:1414
Inline: True
```
**Symbols:**

```
ffffffff8133e290-ffffffff8133e4f4: dax_pmd_load_hole.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81352600)
Location: fs/dax.c:1414
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
