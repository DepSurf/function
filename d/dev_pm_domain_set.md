# Function: <code>dev_pm_domain_set</code>

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
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815a69e0)
Location: drivers/base/power/common.c:144
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_free_dev_data
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff815a69e0-ffffffff815a6a36: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815d51a0)
Location: drivers/base/power/common.c:144
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_free_dev_data
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff815d51a0-ffffffff815d51f6: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815e9c60)
Location: drivers/base/power/common.c:144
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff815e9c60-ffffffff815e9cad: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81651000)
Location: drivers/base/power/common.c:144
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff81651000-ffffffff8165104d: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8168c890)
Location: drivers/base/power/common.c:185
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff8168c890-ffffffff8168c8dc: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816acb80)
Location: drivers/base/power/common.c:202
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff816acb80-ffffffff816acbcc: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816e6630)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff816e6630-ffffffff816e667d: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8170aa00)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff8170aa00-ffffffff8170aa4d: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817c5970)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff817c5970-ffffffff817c59bd: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817da480)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff817da480-ffffffff817da4cd: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817be840)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff817be840-ffffffff817be88d: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81848bc0)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff81848bc0-ffffffff81848c0d: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8198db10)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff8198db10-ffffffff8198db70: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81afda20)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff81afda20-ffffffff81afda80: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81b4be10)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff81b4be10-ffffffff81b4be70: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81ba4250)
Location: drivers/base/power/common.c:220
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/pmdomain/core.c:genpd_remove_device
  - drivers/pmdomain/core.c:genpd_add_device
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/base/power/clock_ops.c:pm_clk_notify
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff81ba4250-ffffffff81ba42b0: dev_pm_domain_set (STB_GLOBAL)
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
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffff8000108f9228)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffff8000108f9228-ffff8000108f928c: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c09e4bbc)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_register
  - arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt
  - arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt
  - drivers/bus/ti-sysc.c:sysc_notifier_call
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
c09e4bbc-c09e4c24: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c0000000009953c0)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
c0000000009953c0-c00000000099544c: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffe000588daa)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffffffe000588daa-ffffffe000588dfc: dev_pm_domain_set (STB_GLOBAL)
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
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816d0150)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff816d0150-ffffffff816d019d: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816ab480)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff816ab480-ffffffff816ab4cd: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816fe6c0)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff816fe6c0-ffffffff816fe70d: dev_pm_domain_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_domain_set(struct device *dev, struct dev_pm_domain *pd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81718f70)
Location: drivers/base/power/common.c:200
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops
```
**Symbols:**

```
ffffffff81718f70-ffffffff81718fbd: dev_pm_domain_set (STB_GLOBAL)
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
