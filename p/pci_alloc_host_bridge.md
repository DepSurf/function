# Function: <code>pci_alloc_host_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81431f64)
Location: drivers/pci/probe.c:521
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147d7a7)
Location: drivers/pci/probe.c:524
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149f0ab)
Location: drivers/pci/probe.c:525
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus_msi
```
**Symbols:**

```
ffffffff8149d0f0-ffffffff8149d126: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8efb)
Location: drivers/pci/probe.c:527
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff814a6ff0-ffffffff814a7031: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7f2b)
Location: drivers/pci/probe.c:527
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff814e5940-ffffffff814e5981: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81514dd0)
Location: drivers/pci/probe.c:539
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81514dd0-ffffffff81514e18: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152a4f0)
Location: drivers/pci/probe.c:538
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff8152a4f0-ffffffff8152a538: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81559c20)
Location: drivers/pci/probe.c:606
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff81559c20-ffffffff81559c7d: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157ac90)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8157ac90-ffffffff8157aced: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81621da5)
Location: drivers/pci/probe.c:601
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81620730-ffffffff816207a9: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81648995)
Location: drivers/pci/probe.c:601
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81646fe0-ffffffff81647059: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81629380)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81629380-ffffffff816293f9: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81698d50)
Location: drivers/pci/probe.c:604
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81698d50-ffffffff81698dd5: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817ba290)
Location: drivers/pci/probe.c:603
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff817ba290-ffffffff817ba312: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d51b0)
Location: drivers/pci/probe.c:603
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff818d51b0-ffffffff818d5234: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81918260)
Location: drivers/pci/probe.c:604
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81918260-ffffffff819182e4: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960d30)
Location: drivers/pci/probe.c:615
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81960d30-ffffffff81960db4: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dd798)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
**Symbols:**

```
ffff8000106dd798-ffff8000106dd7fc: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087929c)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
**Symbols:**

```
c087929c-c08792fc: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000855a80)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
c000000000855a80-c000000000855af4: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b5a28)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffe0004b5a28-ffffffe0004b5a8c: pci_alloc_host_bridge (STB_GLOBAL)
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
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156f1b0)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8156f1b0-ffffffff8156f20d: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155d910)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8155d910-ffffffff8155d96d: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156e9e0)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8156e9e0-ffffffff8156ea3d: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_host_bridge *pci_alloc_host_bridge(size_t priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81588ec0)
Location: drivers/pci/probe.c:602
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff81588ec0-ffffffff81588f1d: pci_alloc_host_bridge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
