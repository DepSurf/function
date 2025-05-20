# Function: <code>devm_kstrdup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154f930)
Location: drivers/base/devres.c:804
Inline: False
```
**Symbols:**

```
ffffffff8154f930-ffffffff8154f98c: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1700)
Location: drivers/base/devres.c:804
Inline: False
```
**Symbols:**

```
ffffffff815a1700-ffffffff815a1763: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cfdb0)
Location: drivers/base/devres.c:805
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff815cfdb0-ffffffff815cfe13: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4910)
Location: drivers/base/devres.c:805
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff815e4910-ffffffff815e4973: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164bbe0)
Location: drivers/base/devres.c:805
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8164bbe0-ffffffff8164bc43: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687200)
Location: drivers/base/devres.c:809
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81687200-ffffffff81687263: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a6dc0)
Location: drivers/base/devres.c:817
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
```
**Symbols:**

```
ffffffff816a6dc0-ffffffff816a6e23: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816dfe90)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
```
**Symbols:**

```
ffffffff816dfe90-ffffffff816dfef6: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817040d0)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817040d0-ffffffff81704136: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817be500)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817be500-ffffffff817be566: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3260)
Location: drivers/base/devres.c:955
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817d3260-ffffffff817d32c6: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b6c70)
Location: drivers/base/devres.c:955
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817b6c70-ffffffff817b6cd2: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840570)
Location: drivers/base/devres.c:944
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81840570-ffffffff818405d2: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff819836a0)
Location: drivers/base/devres.c:944
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
```
**Symbols:**

```
ffffffff819836a0-ffffffff81983719: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af1830)
Location: drivers/base/devres.c:949
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
```
**Symbols:**

```
ffffffff81af1830-ffffffff81af18a9: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b3f9c0)
Location: drivers/base/devres.c:950
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
```
**Symbols:**

```
ffffffff81b3f9c0-ffffffff81b3fa38: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b97840)
Location: drivers/base/devres.c:950
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
```
**Symbols:**

```
ffffffff81b97840-ffffffff81b978b8: devm_kstrdup (STB_GLOBAL)
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
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108efbd0)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffff8000108efbd0-ffff8000108efc44: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dd4a4)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c09dd4a4-c09dd508: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989310)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c000000000989310-c0000000009893cc: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe00058252c)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffe00058252c-ffffffe000582590: devm_kstrdup (STB_GLOBAL)
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
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c9820)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816c9820-ffffffff816c9886: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a4b50)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816a4b50-ffffffff816a4bb6: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f7d90)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816f7d90-ffffffff816f7df6: devm_kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *devm_kstrdup(struct device *dev, const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712630)
Location: drivers/base/devres.c:839
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81712630-ffffffff81712696: devm_kstrdup (STB_GLOBAL)
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
