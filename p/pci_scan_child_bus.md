# Function: <code>pci_scan_child_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81432aa0)
Location: drivers/pci/probe.c:2029
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81432aa0-ffffffff81432bf1: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147e2e0)
Location: drivers/pci/probe.c:2058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8147e2e0-ffffffff8147e45c: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149f9a0)
Location: drivers/pci/probe.c:2208
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8149f9a0-ffffffff8149fb1c: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a9750)
Location: drivers/pci/probe.c:2334
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff814a9750-ffffffff814a98cd: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e8b26)
Location: drivers/pci/probe.c:2606
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff814e8a40-ffffffff814e8a52: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81518165)
Location: drivers/pci/probe.c:2790
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81518080-ffffffff81518092: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152dbe5)
Location: drivers/pci/probe.c:2916
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8152db00-ffffffff8152db12: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155c365)
Location: drivers/pci/probe.c:3142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8155c280-ffffffff8155c292: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157d435)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8157d350-ffffffff8157d362: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81622a25)
Location: drivers/pci/probe.c:2928
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81622940-ffffffff81622952: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81649622)
Location: drivers/pci/probe.c:2935
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81649530-ffffffff81649542: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162c1e2)
Location: drivers/pci/probe.c:2979
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8162c0f0-ffffffff8162c102: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169b6b2)
Location: drivers/pci/probe.c:3021
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8169b5c0-ffffffff8169b5d2: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bce75)
Location: drivers/pci/probe.c:2992
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff817bcd80-ffffffff817bcd9a: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8e05)
Location: drivers/pci/probe.c:3002
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff818d8cf0-ffffffff818d8d0a: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191c145)
Location: drivers/pci/probe.c:3016
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8191c030-ffffffff8191c04a: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81964575)
Location: drivers/pci/probe.c:3065
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81964460-ffffffff8196447a: pci_scan_child_bus (STB_GLOBAL)
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
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0be0)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffff8000106e0ac8-ffff8000106e0af8: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087c95c)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
c087c858-c087c878: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000859cc4)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_scan_phb
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
c000000000859b80-c000000000859b98: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b892c)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
```
**Symbols:**

```
ffffffe0004b8836-ffffffe0004b8864: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81571955)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81571870-ffffffff81571882: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815600b5)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8155ffd0-ffffffff8155ffe2: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81571185)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff815710a0-ffffffff815710b2: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int pci_scan_child_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158b665)
Location: drivers/pci/probe.c:2876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8158b580-ffffffff8158b592: pci_scan_child_bus (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
