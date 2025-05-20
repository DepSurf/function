# Function: <code>dax_insert_entry</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130d040)
Location: fs/dax.c:709
Inline: False
```
**Symbols:**

```
ffffffff8130d040-ffffffff8130d322: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:715
Inline: False
```
**Symbols:**

```
ffffffff813343d0-ffffffff81334607: dax_insert_entry (STB_LOCAL)
ffffffff813367c2-ffffffff813367dd: dax_insert_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81347f90)
Location: fs/dax.c:716
Inline: False
```
**Symbols:**

```
ffffffff81347f90-ffffffff813481db: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138d520)
Location: fs/dax.c:716
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_load_hole
```
**Symbols:**

```
ffffffff8138d520-ffffffff8138d733: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139ecb0)
Location: fs/dax.c:732
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_load_hole
```
**Symbols:**

```
ffffffff8139ecb0-ffffffff8139eec3: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a5dc0)
Location: fs/dax.c:744
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff813a5dc0-ffffffff813a5fd3: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f5830)
Location: fs/dax.c:744
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813f5830-ffffffff813f5a43: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81468990)
Location: fs/dax.c:745
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81468990-ffffffff81468bc0: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct vm_fault *vmf, const struct iomap_iter *iter, void *entry, pfn_t pfn, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f9450)
Location: fs/dax.c:856
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
```
**Symbols:**

```
ffffffff814f9450-ffffffff814f974d: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct vm_fault *vmf, const struct iomap_iter *iter, void *entry, pfn_t pfn, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815308c0)
Location: fs/dax.c:883
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
```
**Symbols:**

```
ffffffff815308c0-ffffffff81530bcb: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct vm_fault *vmf, const struct iomap_iter *iter, void *entry, pfn_t pfn, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815657a0)
Location: fs/dax.c:869
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
```
**Symbols:**

```
ffffffff815657a0-ffffffff81565aa7: dax_insert_entry (STB_LOCAL)
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
In fs/dax.c (ffff800010408b28)
Location: fs/dax.c:716
Inline: True
```
**Symbols:**

```
ffff800010408b28-ffff800010408d80: dax_insert_entry.isra.0 (STB_LOCAL)
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
In fs/dax.c (c000000000514100)
Location: fs/dax.c:716
Inline: True
```
**Symbols:**

```
c000000000514100-c000000000514438: dax_insert_entry.isra.0 (STB_LOCAL)
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
In fs/dax.c (ffffffe0002b2f96)
Location: fs/dax.c:716
Inline: True
```
**Symbols:**

```
ffffffe0002b2f96-ffffffe0002b319e: dax_insert_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81340570)
Location: fs/dax.c:716
Inline: False
```
**Symbols:**

```
ffffffff81340570-ffffffff813407bb: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813311d0)
Location: fs/dax.c:716
Inline: False
```
**Symbols:**

```
ffffffff813311d0-ffffffff81331415: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133e040)
Location: fs/dax.c:716
Inline: False
```
**Symbols:**

```
ffffffff8133e040-ffffffff8133e28b: dax_insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dax_insert_entry(struct xa_state *xas, struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350c70)
Location: fs/dax.c:716
Inline: False
```
**Symbols:**

```
ffffffff81350c70-ffffffff81350eb2: dax_insert_entry (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iomap_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>bool dirty</code>
</li>
<li>
<b>Param reordered. </b>
<code>xas, mapping, vmf, entry, pfn, flags, dirty</code> ➡️ <code>xas, vmf, iter, entry, pfn, flags</code>
</li>
</ul>
</details>
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
