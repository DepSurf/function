# Function: <code>pci_epf_type_add_cfs</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_epf_type_add_cfs(struct pci_epf *epf, struct config_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:34
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_type_make
```
**Symbols:**

```
ffffffff81befc8d-ffffffff81befc9e: pci_epf_type_add_cfs.cold (STB_LOCAL)
ffffffff8165c620-ffffffff8165c6aa: pci_epf_type_add_cfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_epf_type_add_cfs(struct pci_epf *epf, struct config_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:34
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_type_make
```
**Symbols:**

```
ffffffff81ceb191-ffffffff81ceb1a2: pci_epf_type_add_cfs.cold (STB_LOCAL)
ffffffff816cec50-ffffffff816cecda: pci_epf_type_add_cfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_epf_type_add_cfs(struct pci_epf *epf, struct config_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:34
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_type_make
```
**Symbols:**

```
ffffffff81eb25ff-ffffffff81eb2610: pci_epf_type_add_cfs.cold (STB_LOCAL)
ffffffff817f78b0-ffffffff817f793f: pci_epf_type_add_cfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct config_group *pci_epf_type_add_cfs(struct pci_epf *epf, struct config_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819234f0)
Location: drivers/pci/endpoint/pci-epf-core.c:34
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_type_make
```
**Symbols:**

```
ffffffff819234f0-ffffffff81923587: pci_epf_type_add_cfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81965458)
Location: drivers/pci/endpoint/pci-ep-cfs.c:531
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff819aeb08)
Location: drivers/pci/endpoint/pci-ep-cfs.c:531
Inline: True
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
