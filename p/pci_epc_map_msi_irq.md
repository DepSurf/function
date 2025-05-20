# Function: <code>pci_epc_map_msi_irq</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc *epc, u8 func_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 *msi_data, u32 *msi_addr_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165b710)
Location: drivers/pci/endpoint/pci-epc-core.c:253
Inline: False
```
**Symbols:**

```
ffffffff8165b710-ffffffff8165b7b8: pci_epc_map_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 *msi_data, u32 *msi_addr_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816cdbd0)
Location: drivers/pci/endpoint/pci-epc-core.c:263
Inline: False
```
**Symbols:**

```
ffffffff816cdbd0-ffffffff816cdca0: pci_epc_map_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 *msi_data, u32 *msi_addr_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f65e0)
Location: drivers/pci/endpoint/pci-epc-core.c:263
Inline: False
```
**Symbols:**

```
ffffffff817f65e0-ffffffff817f66c9: pci_epc_map_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 *msi_data, u32 *msi_addr_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81922060)
Location: drivers/pci/endpoint/pci-epc-core.c:263
Inline: False
```
**Symbols:**

```
ffffffff81922060-ffffffff81922149: pci_epc_map_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 *msi_data, u32 *msi_addr_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81965ac0)
Location: drivers/pci/endpoint/pci-epc-core.c:263
Inline: False
```
**Symbols:**

```
ffffffff81965ac0-ffffffff81965ba9: pci_epc_map_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epc_map_msi_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t phys_addr, u8 interrupt_num, u32 entry_size, u32 *msi_data, u32 *msi_addr_offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819af1d0)
Location: drivers/pci/endpoint/pci-epc-core.c:262
Inline: False
```
**Symbols:**

```
ffffffff819af1d0-ffffffff819af2b9: pci_epc_map_msi_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, func_no, phys_addr, interrupt_num, entry_size, msi_data, msi_addr_offset</code> ➡️ <code>epc, func_no, vfunc_no, phys_addr, interrupt_num, entry_size, msi_data, msi_addr_offset</code>
</li>
</ul>
</details>
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
