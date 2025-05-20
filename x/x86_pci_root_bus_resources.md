# Function: <code>x86_pci_root_bus_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff816fac00)
Location: arch/x86/pci/bus_numa.c:30
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff816fac00-ffffffff816facd9: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff8175fa90)
Location: arch/x86/pci/bus_numa.c:30
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8175fa90-ffffffff8175fb68: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff8178bfd0)
Location: arch/x86/pci/bus_numa.c:30
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8178bfd0-ffffffff8178c0a8: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff817aaf70)
Location: arch/x86/pci/bus_numa.c:30
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff817aaf70-ffffffff817ab049: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff81822460)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81822460-ffffffff81822539: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8186c882-ffffffff8186c90b: x86_pci_root_bus_resources.cold.2 (STB_LOCAL)
ffffffff8186c750-ffffffff8186c7a0: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8188c892-ffffffff8188c91b: x86_pci_root_bus_resources.cold.1 (STB_LOCAL)
ffffffff8188c760-ffffffff8188c7b0: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff818d71ce-ffffffff818d7259: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff818d70a0-ffffffff818d70e9: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8190954e-ffffffff819095d9: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff81909420-ffffffff81909469: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81bb9e3e-ffffffff81bb9ec7: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff81bb9d10-ffffffff81bb9d56: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81c34a71-ffffffff81c34afa: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff81bce610-ffffffff81bce656: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81c26e59-ffffffff81c26ee2: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff81bc1fc0-ffffffff81bc2006: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81d44de4-ffffffff81d44e6d: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff81c925d0-ffffffff81c92616: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81f11d32-ffffffff81f11dc7: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff81e41cf0-ffffffff81e41d36: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff8201c410)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8201c410-ffffffff8201c4ff: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff8209cab0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8209cab0-ffffffff8209cb9f: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/bus_numa.c (ffffffff82174290)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff82174290-ffffffff8217437f: x86_pci_root_bus_resources (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff818a890e-ffffffff818a8999: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff818a87e0-ffffffff818a8829: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8186331e-ffffffff818633a9: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff818631f0-ffffffff81863239: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff818f9f6e-ffffffff818f9ff9: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff818f9e40-ffffffff818f9e89: x86_pci_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void x86_pci_root_bus_resources(int bus, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/bus_numa.c (0)
Location: arch/x86/pci/bus_numa.c:31
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8191b0ce-ffffffff8191b159: x86_pci_root_bus_resources.cold (STB_LOCAL)
ffffffff8191afa0-ffffffff8191afe9: x86_pci_root_bus_resources (STB_GLOBAL)
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
