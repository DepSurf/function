# Function: <code>pm_generic_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff815548da)
Location: drivers/base/power/generic_ops.c:294
Inline: True
```
**Symbols:**

```
ffffffff81554960-ffffffff8155498c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff815a68da)
Location: drivers/base/power/generic_ops.c:294
Inline: True
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_complete
```
**Symbols:**

```
ffffffff815a6960-ffffffff815a698c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff815d509a)
Location: drivers/base/power/generic_ops.c:294
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:pm_genpd_complete
```
**Symbols:**

```
ffffffff815d5120-ffffffff815d514c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff815e9b5a)
Location: drivers/base/power/generic_ops.c:294
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:pm_genpd_complete
```
**Symbols:**

```
ffffffff815e9be0-ffffffff815e9c0d: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff81650f80)
Location: drivers/base/power/generic_ops.c:293
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff81650f80-ffffffff81650fb0: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff8168c810)
Location: drivers/base/power/generic_ops.c:293
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff8168c810-ffffffff8168c83f: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff816aca40)
Location: drivers/base/power/generic_ops.c:293
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff816aca40-ffffffff816aca6f: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff816e64f0)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff816e64f0-ffffffff816e651c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff8170a8c0)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff8170a8c0-ffffffff8170a8ec: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff817c58a0)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff817c58a0-ffffffff817c58cc: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff817da3b0)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff817da3b0-ffffffff817da3dc: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff817be770)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff817be770-ffffffff817be79c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff81848af0)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff81848af0-ffffffff81848b1c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff8198d970)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff8198d970-ffffffff8198d9ac: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff81afd820)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff81afd820-ffffffff81afd85c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff81b4bc10)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff81b4bc10-ffffffff81b4bc4c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff81ba4000)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pmdomain/core.c:genpd_complete
```
**Symbols:**

```
ffffffff81ba4000-ffffffff81ba403c: pm_generic_complete (STB_GLOBAL)
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
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffff8000108f90f8)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffff8000108f90f8-ffff8000108f913c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (c09e49c4)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
c09e49c4-c09e4a04: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (c000000000995240)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
c000000000995240-c0000000009952a0: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff816d0010)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/acpi/device_pm.c:acpi_subsys_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff816d0010-ffffffff816d003c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff816ab340)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff816ab340-ffffffff816ab36c: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff816fe580)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff816fe580-ffffffff816fe5ac: pm_generic_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_generic_complete(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/generic_ops.c (ffffffff81718dd0)
Location: drivers/base/power/generic_ops.c:291
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/base/power/domain.c:genpd_complete
```
**Symbols:**

```
ffffffff81718dd0-ffffffff81718dfc: pm_generic_complete (STB_GLOBAL)
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
