# Function: <code>shpc_probe</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153be60)
Location: drivers/pci/hotplug/shpchp_core.c:273
Inline: False
```
**Symbols:**

```
ffffffff8153be60-ffffffff8153c21d: shpc_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81553310)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffff81553310-ffffffff815536a7: shpc_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81583205)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffff815831b0-ffffffff81583481: shpc_probe (STB_LOCAL)
ffffffff815835fb-ffffffff8158369c: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815a4be5)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffff815a4b90-ffffffff815a4e61: shpc_probe (STB_LOCAL)
ffffffff815a4fdb-ffffffff815a507c: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: False
```
**Symbols:**

```
ffffffff8164da10-ffffffff8164daee: shpc_probe (STB_LOCAL)
ffffffff8164dcf0-ffffffff8164dd31: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: False
```
**Symbols:**

```
ffffffff81671bd0-ffffffff81671cae: shpc_probe (STB_LOCAL)
ffffffff81bfc549-ffffffff81bfc58a: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: False
```
**Symbols:**

```
ffffffff816540e0-ffffffff816541be: shpc_probe (STB_LOCAL)
ffffffff81bee434-ffffffff81bee475: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: False
```
**Symbols:**

```
ffffffff816c5f10-ffffffff816c5ffa: shpc_probe (STB_LOCAL)
ffffffff81ce9347-ffffffff81ce939c: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: False
```
**Symbols:**

```
ffffffff817ebdf0-ffffffff817ebee4: shpc_probe (STB_LOCAL)
ffffffff81eb03e0-ffffffff81eb0434: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: False
```
**Symbols:**

```
ffffffff819124e0-ffffffff81912606: shpc_probe (STB_LOCAL)
ffffffff8208fa35-ffffffff8208fa4a: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:254
Inline: False
```
**Symbols:**

```
ffffffff81955b70-ffffffff81955c96: shpc_probe (STB_LOCAL)
ffffffff8210fd95-ffffffff8210fdaa: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:254
Inline: False
```
**Symbols:**

```
ffffffff8199f060-ffffffff8199f1b8: shpc_probe (STB_LOCAL)
ffffffff821edabd-ffffffff821edad2: shpc_probe.cold (STB_LOCAL)
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
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d8f0)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffff80001070d8f0-ffff80001070dc7c: shpc_probe (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9fde)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffe0004d9fde-ffffffe0004da302: shpc_probe (STB_LOCAL)
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
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815983f5)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffff815983a0-ffffffff81598671: shpc_probe (STB_LOCAL)
ffffffff815987eb-ffffffff8159888c: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81587585)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffff81587530-ffffffff81587801: shpc_probe (STB_LOCAL)
ffffffff8158797b-ffffffff81587a1c: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598935)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffff815988e0-ffffffff81598bb1: shpc_probe (STB_LOCAL)
ffffffff81598d2b-ffffffff81598dcc: shpc_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shpc_probe(struct pci_dev *pdev, const struct pci_device_id *ent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815b2d75)
Location: drivers/pci/hotplug/shpchp_core.c:255
Inline: True
```
**Symbols:**

```
ffffffff815b2d20-ffffffff815b2ff1: shpc_probe (STB_LOCAL)
ffffffff815b316b-ffffffff815b320c: shpc_probe.cold (STB_LOCAL)
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
