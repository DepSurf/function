# Function: <code>dw_pcie_allocate_domains</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815493f0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:269
Inline: True
```
**Symbols:**

```
ffffffff815493f0-ffffffff815494a2: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155faf0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:275
Inline: True
```
**Symbols:**

```
ffffffff8155faf0-ffffffff8155fba2: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8159058a)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:253
Inline: True
```
**Symbols:**

```
ffffffff81590570-ffffffff815905b0: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff815903f0-ffffffff8159046c: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b22ba)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
```
**Symbols:**

```
ffffffff815b22a0-ffffffff815b22e0: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff815b2120-ffffffff815b219c: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:255
Inline: False
```
**Symbols:**

```
ffffffff8165bc72-ffffffff8165bcb2: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff8165bae0-ffffffff8165bb6d: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:233
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81bfe192-ffffffff81bfe1cf: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff8167bef0-ffffffff8167bf71: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:233
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81befdfb-ffffffff81befe38: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff8165edb0-ffffffff8165ee31: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:232
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81ceb450-ffffffff81ceb48d: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff816d1960-ffffffff816d19e1: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:232
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81eb2843-ffffffff81eb2878: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff817faa40-ffffffff817faad3: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_allocate_domains(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81927240)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:231
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
**Symbols:**

```
ffffffff81927240-ffffffff81927300: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_allocate_domains(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b410)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:231
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
**Symbols:**

```
ffffffff8196b410-ffffffff8196b4d0: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_allocate_domains(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4ef0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:233
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
**Symbols:**

```
ffffffff819b4ef0-ffffffff819b4fb0: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072ebd0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_host_init
```
**Symbols:**

```
ffff80001072ebd0-ffff80001072ec8c: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b8088)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
c08b8088-c08b8148: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8ebc)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffe0004e8ebc-ffffffe0004e8f68: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5a7a)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
```
**Symbols:**

```
ffffffff815a5a60-ffffffff815a5aa0: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff815a58e0-ffffffff815a595c: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594c1a)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
```
**Symbols:**

```
ffffffff81594c00-ffffffff81594c40: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff81594a80-ffffffff81594afc: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a600a)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
```
**Symbols:**

```
ffffffff815a5ff0-ffffffff815a6030: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff815a5e70-ffffffff815a5eec: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_allocate_domains(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c040a)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:254
Inline: True
```
**Symbols:**

```
ffffffff815c03f0-ffffffff815c0430: dw_pcie_allocate_domains.cold (STB_LOCAL)
ffffffff815c0270-ffffffff815c02ec: dw_pcie_allocate_domains (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<b>Param type changed. </b>
<code>struct pcie_port *pp</code> ➡️ <code>struct dw_pcie_rp *pp</code>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
