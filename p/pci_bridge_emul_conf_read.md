# Function: <code>pci_bridge_emul_conf_read</code>

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
int pci_bridge_emul_conf_read(struct pci_bridge_emul *bridge, int where, int size, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-bridge-emul.c (ffff800010718438)
Location: drivers/pci/pci-bridge-emul.c:323
Inline: False
Direct callers:
  - drivers/pci/pci-bridge-emul.c:pci_bridge_emul_conf_write
  - drivers/pci/pci-bridge-emul.c:pci_bridge_emul_conf_write
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
```
**Symbols:**

```
ffff800010718438-ffff8000107185d4: pci_bridge_emul_conf_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bridge_emul_conf_read(struct pci_bridge_emul *bridge, int where, int size, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-bridge-emul.c (c08a2ad8)
Location: drivers/pci/pci-bridge-emul.c:323
Inline: False
Direct callers:
  - drivers/pci/pci-bridge-emul.c:pci_bridge_emul_conf_write
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf
```
**Symbols:**

```
c08a2ad8-c08a2bf4: pci_bridge_emul_conf_read (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
