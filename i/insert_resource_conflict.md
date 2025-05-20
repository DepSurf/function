# Function: <code>insert_resource_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81087640)
Location: kernel/resource.c:817
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81087640-ffffffff81087675: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089412)
Location: kernel/resource.c:851
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8108a570-ffffffff8108a5a5: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e362)
Location: kernel/resource.c:851
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8108f4c0-ffffffff8108f4f5: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b382)
Location: kernel/resource.c:851
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8108c470-ffffffff8108c4a5: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092062)
Location: kernel/resource.c:869
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810931b0-ffffffff810931e5: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096bd0)
Location: kernel/resource.c:838
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81096bd0-ffffffff81096c05: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109eef0)
Location: kernel/resource.c:832
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8109eef0-ffffffff8109ef25: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3520)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810a3520-ffffffff810a3557: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9b50)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810a9b50-ffffffff810a9b87: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0dc5)
Location: kernel/resource.c:846
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810b1710-ffffffff810b1747: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac533)
Location: kernel/resource.c:853
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810ace70-ffffffff810acea7: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad753)
Location: kernel/resource.c:845
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810ae050-ffffffff810ae087: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bf2d3)
Location: kernel/resource.c:845
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810bfbd0-ffffffff810bfc07: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6632)
Location: kernel/resource.c:832
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810d7080-ffffffff810d70c8: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f5772)
Location: kernel/resource.c:833
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810f6b00-ffffffff810f6b48: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101bb2)
Location: kernel/resource.c:833
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81102f10-ffffffff81102f58: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b302)
Location: kernel/resource.c:888
Inline: True
Inline callers:
  - kernel/resource.c:insert_resource
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_reserved
```
**Symbols:**

```
ffffffff8110c840-ffffffff8110c888: insert_resource_conflict (STB_GLOBAL)
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
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101aa0)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffff800010101aa0-ffff800010101b3c: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035df2c)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
c035df2c-c035df7c: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001492a0)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
c0000000001492a0-c000000000149308: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8bb2)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffe0000c8bb2-ffffffe0000c8c00: insert_resource_conflict (STB_GLOBAL)
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
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3470)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810a3470-ffffffff810a34a7: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091e50)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81091e50-ffffffff81091e87: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3420)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810a3420-ffffffff810a3457: insert_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct resource *insert_resource_conflict(struct resource *parent, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab4c0)
Location: kernel/resource.c:846
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff810ab4c0-ffffffff810ab502: insert_resource_conflict (STB_GLOBAL)
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
