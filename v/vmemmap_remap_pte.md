# Function: <code>vmemmap_remap_pte</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vmemmap_remap_pte(pte_t *pte, long unsigned int addr, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8132c3d0)
Location: mm/sparse-vmemmap.c:233
Inline: False
```
**Symbols:**

```
ffffffff8132c3d0-ffffffff8132c4a2: vmemmap_remap_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vmemmap_remap_pte(pte_t *pte, long unsigned int addr, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8139c350)
Location: mm/sparse-vmemmap.c:259
Inline: False
```
**Symbols:**

```
ffffffff8139c350-ffffffff8139c440: vmemmap_remap_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmemmap_remap_pte(pte_t *pte, long unsigned int addr, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff814143c0)
Location: mm/hugetlb_vmemmap.c:234
Inline: False
```
**Symbols:**

```
ffffffff814143c0-ffffffff81414514: vmemmap_remap_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmemmap_remap_pte(pte_t *pte, long unsigned int addr, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81447920)
Location: mm/hugetlb_vmemmap.c:234
Inline: False
```
**Symbols:**

```
ffffffff81447920-ffffffff81447a70: vmemmap_remap_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vmemmap_remap_pte(pte_t *pte, long unsigned int addr, struct vmemmap_remap_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_vmemmap.c (ffffffff81481020)
Location: mm/hugetlb_vmemmap.c:202
Inline: False
```
**Symbols:**

```
ffffffff81481020-ffffffff81481181: vmemmap_remap_pte (STB_LOCAL)
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
