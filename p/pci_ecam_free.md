# Function: <code>pci_ecam_free</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_ecam_free(struct pci_config_window *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (ffff8000107198a8)
Location: drivers/pci/ecam.c:105
Inline: False
Direct callers:
  - arch/arm64/kernel/pci.c:pci_acpi_generic_release_info
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
**Symbols:**

```
ffff8000107198a8-ffff8000107198f0: pci_ecam_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_ecam_free(struct pci_config_window *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (c08a33dc)
Location: drivers/pci/ecam.c:105
Inline: False
Direct callers:
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
**Symbols:**

```
c08a33dc-c08a3470: pci_ecam_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_ecam_free(struct pci_config_window *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (c000000000889630)
Location: drivers/pci/ecam.c:105
Inline: False
Direct callers:
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
**Symbols:**

```
c000000000889630-c0000000008896a0: pci_ecam_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_ecam_free(struct pci_config_window *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (ffffffe0004e14ca)
Location: drivers/pci/ecam.c:105
Inline: False
Direct callers:
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
**Symbols:**

```
ffffffe0004e14ca-ffffffe0004e150e: pci_ecam_free (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
