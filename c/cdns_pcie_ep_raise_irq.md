# Function: <code>cdns_pcie_ep_raise_irq</code>

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
int cdns_pcie_ep_raise_irq(struct pci_epc *epc, u8 fn, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e8c0)
Location: drivers/pci/controller/pcie-cadence-ep.c:363
Inline: False
```
**Symbols:**

```
ffff80001071e8c0-ffff80001071eacc: cdns_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdns_pcie_ep_raise_irq(struct pci_epc *epc, u8 fn, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (c08a77d4)
Location: drivers/pci/controller/pcie-cadence-ep.c:363
Inline: False
```
**Symbols:**

```
c08a77d4-c08a79a4: cdns_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdns_pcie_ep_raise_irq(struct pci_epc *epc, u8 fn, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088fe90)
Location: drivers/pci/controller/pcie-cadence-ep.c:363
Inline: False
```
**Symbols:**

```
c00000000088fe90-c00000000089029c: cdns_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdns_pcie_ep_raise_irq(struct pci_epc *epc, u8 fn, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e57d6)
Location: drivers/pci/controller/pcie-cadence-ep.c:363
Inline: False
```
**Symbols:**

```
ffffffe0004e57d6-ffffffe0004e5978: cdns_pcie_ep_raise_irq (STB_LOCAL)
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
