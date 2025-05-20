# Function: <code>pci_dpc_init</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:258
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff8163e8be-ffffffff8163e8e0: pci_dpc_init.cold (STB_LOCAL)
ffffffff8163e470-ffffffff8163e4fa: pci_dpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:261
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff81bf9ec6-ffffffff81bf9ee8: pci_dpc_init.cold (STB_LOCAL)
ffffffff81664b90-ffffffff81664c1a: pci_dpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81bebd1d-ffffffff81bebd3f: pci_dpc_init.cold (STB_LOCAL)
ffffffff81647140-ffffffff816471ca: pci_dpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81ce68f8-ffffffff81ce6917: pci_dpc_init.cold (STB_LOCAL)
ffffffff816b89f0-ffffffff816b8a7d: pci_dpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81ead4b4-ffffffff81ead4d3: pci_dpc_init.cold (STB_LOCAL)
ffffffff817dced0-ffffffff817dcf6f: pci_dpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff818ff3d0)
Location: drivers/pci/pcie/dpc.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff818ff3d0-ffffffff818ff48f: pci_dpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81942940)
Location: drivers/pci/pcie/dpc.c:324
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81942940-ffffffff819429ff: pci_dpc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_dpc_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8198bc10)
Location: drivers/pci/pcie/dpc.c:335
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8198bc10-ffffffff8198bccf: pci_dpc_init (STB_GLOBAL)
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
