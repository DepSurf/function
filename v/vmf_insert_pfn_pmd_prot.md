# Function: <code>vmf_insert_pfn_pmd_prot</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault *vmf, pfn_t pfn, pgprot_t pgprot, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812e98c0)
Location: mm/huge_memory.c:838
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff812e98c0-ffffffff812e9bac: vmf_insert_pfn_pmd_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault *vmf, pfn_t pfn, pgprot_t pgprot, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f5690)
Location: mm/huge_memory.c:830
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff812f5690-ffffffff812f597c: vmf_insert_pfn_pmd_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault *vmf, pfn_t pfn, pgprot_t pgprot, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fa9f0)
Location: mm/huge_memory.c:846
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff812fa9f0-ffffffff812faabf: vmf_insert_pfn_pmd_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault *vmf, pfn_t pfn, pgprot_t pgprot, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813445f0)
Location: mm/huge_memory.c:846
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813445f0-ffffffff813448f5: vmf_insert_pfn_pmd_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault *vmf, pfn_t pfn, pgprot_t pgprot, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bac00)
Location: mm/huge_memory.c:840
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813bac00-ffffffff813baf2a: vmf_insert_pfn_pmd_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd_prot(struct vm_fault *vmf, pfn_t pfn, pgprot_t pgprot, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143d0b0)
Location: mm/huge_memory.c:900
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff8143d0b0-ffffffff8143d3e5: vmf_insert_pfn_pmd_prot (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
