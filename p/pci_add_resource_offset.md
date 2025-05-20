# Function: <code>pci_add_resource_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f0b0)
Location: drivers/pci/bus.c:20
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8142f0b0-ffffffff8142f104: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147a700)
Location: drivers/pci/bus.c:20
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8147a700-ffffffff8147a754: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149bb80)
Location: drivers/pci/bus.c:20
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8149bb80-ffffffff8149bbd4: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a5960)
Location: drivers/pci/bus.c:20
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff814a5960-ffffffff814a59b4: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e47a0)
Location: drivers/pci/bus.c:20
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff814e47a0-ffffffff814e47f4: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8151451a-ffffffff8151452e: pci_add_resource_offset.cold.9 (STB_LOCAL)
ffffffff81513c90-ffffffff81513cd7: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff81529c7a-ffffffff81529c8e: pci_add_resource_offset.cold.8 (STB_LOCAL)
ffffffff815293f0-ffffffff81529437: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff81558e7a-ffffffff81558e8e: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff81558680-ffffffff815586c7: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8157a46d-ffffffff8157a481: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff81579c60-ffffffff81579ca7: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8161f155)
Location: drivers/pci/bus.c:19
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8161f57d-ffffffff8161f591: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff8161ecd0-ffffffff8161ed17: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff81645954)
Location: drivers/pci/bus.c:19
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff81bf6e7a-ffffffff81bf6e8e: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff816454c0-ffffffff81645507: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff81628694)
Location: drivers/pci/bus.c:19
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff81be8ce9-ffffffff81be8cfd: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff81628200-ffffffff81628247: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff81697fe4)
Location: drivers/pci/bus.c:19
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff81ce30e4-ffffffff81ce30f8: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff81697b00-ffffffff81697b47: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff817b928e)
Location: drivers/pci/bus.c:19
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff81ea9bd8-ffffffff81ea9bec: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff817b8ef0-ffffffff817b8f43: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d3dbe)
Location: drivers/pci/bus.c:19
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff818d39d0-ffffffff818d3a30: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81916eee)
Location: drivers/pci/bus.c:20
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff81916b00-ffffffff81916b60: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195efbe)
Location: drivers/pci/bus.c:20
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8195ebd0-ffffffff8195ec30: pci_add_resource_offset (STB_GLOBAL)
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
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dc398)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
**Symbols:**

```
ffff8000106dc398-ffff8000106dc404: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c08781d8)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
**Symbols:**

```
c08781d8-c087823c: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c0000000008542e0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_scan_phb
  - arch/powerpc/kernel/pci-common.c:pcibios_scan_phb
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
**Symbols:**

```
c0000000008542e0-c000000000854378: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b49bc)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
**Symbols:**

```
ffffffe0004b49bc-ffffffe0004b4a18: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8156e97d-ffffffff8156e991: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff8156e180-ffffffff8156e1c7: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8155d0ed-ffffffff8155d101: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff8155c8e0-ffffffff8155c927: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8156e1bd-ffffffff8156e1d1: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff8156d9b0-ffffffff8156d9f7: pci_add_resource_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_add_resource_offset(struct list_head *resources, struct resource *res, resource_size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:19
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_add_resource
```
**Symbols:**

```
ffffffff8158869d-ffffffff815886b1: pci_add_resource_offset.cold (STB_LOCAL)
ffffffff81587e90-ffffffff81587ed7: pci_add_resource_offset (STB_GLOBAL)
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
