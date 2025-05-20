# Function: <code>pci_create_root_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81431eb0)
Location: drivers/pci/probe.c:2091
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81431eb0-ffffffff814322eb: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147d6e0)
Location: drivers/pci/probe.c:2129
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8147d6e0-ffffffff8147daf4: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149fb85)
Location: drivers/pci/probe.c:2310
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bus
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8149f1a0-ffffffff8149f1b3: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8ee0)
Location: drivers/pci/probe.c:2405
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff814a8ee0-ffffffff814a8fca: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7f10)
Location: drivers/pci/probe.c:2632
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff814e7f10-ffffffff814e7ffa: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815175a0)
Location: drivers/pci/probe.c:2816
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff815175a0-ffffffff8151765e: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152d020)
Location: drivers/pci/probe.c:2942
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8152d020-ffffffff8152d0dd: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155b7c0)
Location: drivers/pci/probe.c:3168
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8155b7c0-ffffffff8155b881: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157c870)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8157c870-ffffffff8157c931: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81621da0)
Location: drivers/pci/probe.c:2954
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81621da0-ffffffff81621ec1: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81648990)
Location: drivers/pci/probe.c:2961
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81648990-ffffffff81648ab1: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162b5b0)
Location: drivers/pci/probe.c:3005
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8162b5b0-ffffffff8162b671: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169aa80)
Location: drivers/pci/probe.c:3047
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8169aa80-ffffffff8169ab41: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bc210)
Location: drivers/pci/probe.c:3018
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff817bc210-ffffffff817bc2d9: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8080)
Location: drivers/pci/probe.c:3028
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff818d8080-ffffffff818d8149: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191b350)
Location: drivers/pci/probe.c:3042
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8191b350-ffffffff8191b419: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81963780)
Location: drivers/pci/probe.c:3091
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81963780-ffffffff81963849: pci_create_root_bus (STB_GLOBAL)
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
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dffb0)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffff8000106dffb0-ffff8000106e0068: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087bc74)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
```
**Symbols:**

```
c087bc74-c087bd1c: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000858cd0)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_scan_phb
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
```
**Symbols:**

```
c000000000858cd0-c000000000858dc4: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7ee4)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
```
**Symbols:**

```
ffffffe0004b7ee4-ffffffe0004b7f8a: pci_create_root_bus (STB_GLOBAL)
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
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81570d90)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff81570d90-ffffffff81570e51: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155f4f0)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8155f4f0-ffffffff8155f5b1: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815705c0)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff815705c0-ffffffff81570681: pci_create_root_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_bus *pci_create_root_bus(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158aaa0)
Location: drivers/pci/probe.c:2902
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8158aaa0-ffffffff8158ab61: pci_create_root_bus (STB_GLOBAL)
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
