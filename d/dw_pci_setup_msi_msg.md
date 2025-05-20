# Function: <code>dw_pci_setup_msi_msg</code>

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
void dw_pci_setup_msi_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81548ee0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:126
Inline: False
```
**Symbols:**

```
ffffffff81548ee0-ffffffff81548f80: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155f5c0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:123
Inline: False
```
**Symbols:**

```
ffffffff8155f5c0-ffffffff8155f660: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:123
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:125
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b6c0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:102
Inline: False
```
**Symbols:**

```
ffffffff8167b6c0-ffffffff8167b705: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e550)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:102
Inline: False
```
**Symbols:**

```
ffffffff8165e550-ffffffff8165e594: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1020)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:101
Inline: False
```
**Symbols:**

```
ffffffff816d1020-ffffffff816d1061: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817f9e60)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:101
Inline: False
```
**Symbols:**

```
ffffffff817f9e60-ffffffff817f9ec9: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926530)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:100
Inline: False
```
**Symbols:**

```
ffffffff81926530-ffffffff81926599: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196a710)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:100
Inline: False
```
**Symbols:**

```
ffffffff8196a710-ffffffff8196a779: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b3ed0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:102
Inline: False
```
**Symbols:**

```
ffffffff819b3ed0-ffffffff819b3f39: dw_pci_setup_msi_msg (STB_LOCAL)
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
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072dd30)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
```
**Symbols:**

```
ffff80001072dd30-ffff80001072dd9c: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b757c)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
```
**Symbols:**

```
c08b757c-c08b75f0: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dw_pci_setup_msi_msg(struct irq_data *d, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8480)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
```
**Symbols:**

```
ffffffe0004e8480-ffffffe0004e84f2: dw_pci_setup_msi_msg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:124
Inline: False
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
</ul>
