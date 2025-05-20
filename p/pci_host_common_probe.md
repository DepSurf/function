# Function: <code>pci_host_common_probe</code>

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
int pci_host_common_probe(struct platform_device *pdev, struct pci_ecam_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-host-common.c (ffff800010722fb8)
Location: drivers/pci/controller/pci-host-common.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:gen_pci_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_almost_ecam_probe
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_probe
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_probe
```
**Symbols:**

```
ffff800010722fb8-ffff800010723194: pci_host_common_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_host_common_probe(struct platform_device *pdev, struct pci_ecam_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-host-common.c (c08afc70)
Location: drivers/pci/controller/pci-host-common.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:gen_pci_probe
```
**Symbols:**

```
c08afc70-c08afe54: pci_host_common_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_host_common_probe(struct platform_device *pdev, struct pci_ecam_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-host-common.c (c000000000891670)
Location: drivers/pci/controller/pci-host-common.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:gen_pci_probe
```
**Symbols:**

```
c000000000891670-c0000000008918fc: pci_host_common_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_host_common_probe(struct platform_device *pdev, struct pci_ecam_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-host-common.c (ffffffe0004e6818)
Location: drivers/pci/controller/pci-host-common.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:gen_pci_probe
```
**Symbols:**

```
ffffffe0004e6818-ffffffe0004e69aa: pci_host_common_probe (STB_GLOBAL)
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
