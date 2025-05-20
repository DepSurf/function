# Function: <code>pci_epf_remove_vepf</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_epf_remove_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816cf0d0)
Location: drivers/pci/endpoint/pci-epf-core.c:230
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_unlink
```
**Symbols:**

```
ffffffff816cf0d0-ffffffff816cf16a: pci_epf_remove_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_epf_remove_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f7d90)
Location: drivers/pci/endpoint/pci-epf-core.c:230
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_unlink
```
**Symbols:**

```
ffffffff817f7d90-ffffffff817f7e3d: pci_epf_remove_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_epf_remove_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81923900)
Location: drivers/pci/endpoint/pci-epf-core.c:230
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_unlink
```
**Symbols:**

```
ffffffff81923900-ffffffff819239ad: pci_epf_remove_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_epf_remove_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81967510)
Location: drivers/pci/endpoint/pci-epf-core.c:198
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_unlink
```
**Symbols:**

```
ffffffff81967510-ffffffff819675bd: pci_epf_remove_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_epf_remove_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b0c40)
Location: drivers/pci/endpoint/pci-epf-core.c:198
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_unlink
```
**Symbols:**

```
ffffffff819b0c40-ffffffff819b0ced: pci_epf_remove_vepf (STB_GLOBAL)
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
