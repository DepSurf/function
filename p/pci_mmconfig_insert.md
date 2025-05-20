# Function: <code>pci_mmconfig_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff816f7130)
Location: arch/x86/pci/mmconfig-shared.c:724
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff816f7130-ffffffff816f732d: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175bdc0)
Location: arch/x86/pci/mmconfig-shared.c:724
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff8175bdc0-ffffffff8175bfc3: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81788330)
Location: arch/x86/pci/mmconfig-shared.c:724
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81788330-ffffffff81788533: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a7430)
Location: arch/x86/pci/mmconfig-shared.c:724
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff817a7430-ffffffff817a7636: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e690)
Location: arch/x86/pci/mmconfig-shared.c:725
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff8181e690-ffffffff8181e896: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818688e0)
Location: arch/x86/pci/mmconfig-shared.c:720
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff818688e0-ffffffff81868ae8: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81888960)
Location: arch/x86/pci/mmconfig-shared.c:720
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81888960-ffffffff81888b68: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:720
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff818d34e9-ffffffff818d357c: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff818d3290-ffffffff818d3417: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81905869-ffffffff819058fc: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81905610-ffffffff81905797: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:setup_mcfg_map
```
**Symbols:**

```
ffffffff81bb5e19-ffffffff81bb5eac: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81bb5bd0-ffffffff81bb5d4b: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:setup_mcfg_map
```
**Symbols:**

```
ffffffff81c34064-ffffffff81c340f7: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81bcad80-ffffffff81bcaefb: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81c263d7-ffffffff81c2646a: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81bbe6c0-ffffffff81bbe83b: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81d4415d-ffffffff81d44220: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81c8e600-ffffffff81c8e79d: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81f10f9f-ffffffff81f11062: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81e3d6a0-ffffffff81e3d849: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:753
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff820b71bc-ffffffff820b71ec: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff82016af0-ffffffff82016d22: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:753
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff8213855a-ffffffff8213858a: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff82096ea0-ffffffff820970d6: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:764
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff8221a48b-ffffffff8221a4bb: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff8216e340-ffffffff8216e5bb: pci_mmconfig_insert (STB_GLOBAL)
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
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff818a4c29-ffffffff818a4cbc: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff818a49d0-ffffffff818a4b57: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff818603e9-ffffffff8186047c: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81860190-ffffffff81860317: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff818f6289-ffffffff818f631c: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff818f6030-ffffffff818f61b7: pci_mmconfig_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_mmconfig_insert(struct device *dev, u16 seg, u8 start, u8 end, phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (0)
Location: arch/x86/pci/mmconfig-shared.c:721
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81917379-ffffffff8191740c: pci_mmconfig_insert.cold (STB_LOCAL)
ffffffff81917120-ffffffff819172a7: pci_mmconfig_insert (STB_GLOBAL)
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
