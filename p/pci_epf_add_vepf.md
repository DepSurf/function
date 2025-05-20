# Function: <code>pci_epf_add_vepf</code>

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
int pci_epf_add_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816cece0)
Location: drivers/pci/endpoint/pci-epf-core.c:187
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_link
```
**Symbols:**

```
ffffffff816cece0-ffffffff816cee29: pci_epf_add_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_epf_add_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f7940)
Location: drivers/pci/endpoint/pci-epf-core.c:187
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_link
```
**Symbols:**

```
ffffffff817f7940-ffffffff817f7a96: pci_epf_add_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epf_add_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81923ea0)
Location: drivers/pci/endpoint/pci-epf-core.c:187
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_link
```
**Symbols:**

```
ffffffff81923ea0-ffffffff81923fe8: pci_epf_add_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epf_add_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81967ab0)
Location: drivers/pci/endpoint/pci-epf-core.c:155
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_link
```
**Symbols:**

```
ffffffff81967ab0-ffffffff81967bf8: pci_epf_add_vepf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epf_add_vepf(struct pci_epf *epf_pf, struct pci_epf *epf_vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b1210)
Location: drivers/pci/endpoint/pci-epf-core.c:155
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_link
```
**Symbols:**

```
ffffffff819b1210-ffffffff819b1358: pci_epf_add_vepf (STB_GLOBAL)
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
