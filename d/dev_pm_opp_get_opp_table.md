# Function: <code>dev_pm_opp_get_opp_table</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d5030)
Location: drivers/opp/core.c:842
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff817d5030-ffffffff817d5176: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181de10)
Location: drivers/opp/core.c:849
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff8181de10-ffffffff8181df54: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8184a4c5)
Location: drivers/opp/core.c:908
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_genpd_virt_dev
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81849c80-ffffffff81849c90: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d2a5)
Location: drivers/opp/core.c:982
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff8188ca40-ffffffff8188ca50: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf4e5)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff818bebc0-ffffffff818bebd0: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81990ce5)
Location: drivers/opp/core.c:1114
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81990230-ffffffff81990281: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81c2909d-ffffffff81c290bc: dev_pm_opp_get_opp_table.cold (STB_LOCAL)
ffffffff81992350-ffffffff819923a0: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1355
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81c1b1b1-ffffffff81c1b1d0: dev_pm_opp_get_opp_table.cold (STB_LOCAL)
ffffffff819769b0-ffffffff81976a00: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1365
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81d2b230-ffffffff81d2b24f: dev_pm_opp_get_opp_table.cold (STB_LOCAL)
ffffffff81a1f780-ffffffff81a1f7d0: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1510
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81ef7405-ffffffff81ef7424: dev_pm_opp_get_opp_table.cold (STB_LOCAL)
ffffffff81b881f0-ffffffff81b88247: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d27c70)
Location: drivers/opp/core.c:1482
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81d27c70-ffffffff81d27cea: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d90e10)
Location: drivers/opp/core.c:1498
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81d90e10-ffffffff81d90e8a: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e484e0)
Location: drivers/opp/core.c:1609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81e484e0-ffffffff81e4855a: dev_pm_opp_get_opp_table (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a8ec)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffff800010b19d30-ffff800010b19d60: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf5440)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
c0bf49f8-c0bf4a18: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0c70c)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
c000000000c0b840-c000000000c0b858: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702f76)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffffffe0007025e8-ffffffe000702614: dev_pm_opp_get_opp_table (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81863c05)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff818632e0-ffffffff818632f0: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182c8b5)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff8182bf90-ffffffff8182bfa0: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4995)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff818b4070-ffffffff818b4080: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0c45)
Location: drivers/opp/core.c:1031
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff818d0320-ffffffff818d0330: dev_pm_opp_get_opp_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
