# Function: <code>pci_unmap_iospace</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81483a20)
Location: drivers/pci/pci.c:3357
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff81483a20-ffffffff81483a2b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5180)
Location: drivers/pci/pci.c:3395
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff814a5180-ffffffff814a518b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aa300)
Location: drivers/pci/pci.c:3450
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff814aa300-ffffffff814aa30b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814e9560)
Location: drivers/pci/pci.c:3465
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff814e9560-ffffffff814e956b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81518cf0)
Location: drivers/pci/pci.c:3611
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff81518cf0-ffffffff81518cfb: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152e760)
Location: drivers/pci/pci.c:3876
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8152e760-ffffffff8152e76b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155df10)
Location: drivers/pci/pci.c:3974
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8155df10-ffffffff8155df1b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157ef80)
Location: drivers/pci/pci.c:3970
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8157ef80-ffffffff8157ef8b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81624510)
Location: drivers/pci/pci.c:4041
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff81624510-ffffffff8162451b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164a0d0)
Location: drivers/pci/pci.c:4109
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8164a0d0-ffffffff8164a0db: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162ccc0)
Location: drivers/pci/pci.c:4141
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8162ccc0-ffffffff8162cccb: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169bf30)
Location: drivers/pci/pci.c:4191
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8169bf30-ffffffff8169bf3b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bd860)
Location: drivers/pci/pci.c:4287
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff817bd860-ffffffff817bd86f: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818d99f0)
Location: drivers/pci/pci.c:4230
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff818d99f0-ffffffff818d99ff: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191cd40)
Location: drivers/pci/pci.c:4268
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8191cd40-ffffffff8191cd4f: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81965170)
Location: drivers/pci/pci.c:4378
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff81965170-ffffffff8196517f: pci_unmap_iospace (STB_GLOBAL)
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
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e2e20)
Location: drivers/pci/pci.c:3970
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_unmap_iospace
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffff8000106e2db8-ffff8000106e2dfc: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087eaf0)
Location: drivers/pci/pci.c:3970
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_unmap_iospace
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
**Symbols:**

```
c087eaac-c087ead8: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085ade0)
Location: drivers/pci/pci.c:3970
Inline: True
```
**Symbols:**

```
c00000000085ade0-c00000000085adec: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba5a8)
Location: drivers/pci/pci.c:3970
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_unmap_iospace
```
**Symbols:**

```
ffffffe0004ba558-ffffffe0004ba590: pci_unmap_iospace (STB_GLOBAL)
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
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815734a0)
Location: drivers/pci/pci.c:3970
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff815734a0-ffffffff815734ab: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561c00)
Location: drivers/pci/pci.c:3970
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff81561c00-ffffffff81561c0b: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81572cd0)
Location: drivers/pci/pci.c:3970
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff81572cd0-ffffffff81572cdb: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_iospace(struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158d1b0)
Location: drivers/pci/pci.c:3970
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
```
**Symbols:**

```
ffffffff8158d1b0-ffffffff8158d1bb: pci_unmap_iospace (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
