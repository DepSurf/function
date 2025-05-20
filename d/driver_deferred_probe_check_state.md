# Function: <code>driver_deferred_probe_check_state</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a2d10)
Location: drivers/base/dd.c:245
Inline: False
```
**Symbols:**

```
ffffffff816a2d10-ffffffff816a2d77: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:262
Inline: False
```
**Symbols:**

```
ffffffff816dc387-ffffffff816dc3a0: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff816dbab0-ffffffff816dbaed: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:262
Inline: False
```
**Symbols:**

```
ffffffff81700434-ffffffff8170044d: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff816ffac0-ffffffff816ffafd: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:254
Inline: False
```
**Symbols:**

```
ffffffff817ba3a3-ffffffff817ba3b9: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff817b99e0-ffffffff817b9a08: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:278
Inline: False
```
**Symbols:**

```
ffffffff81c0e42e-ffffffff81c0e444: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff817cea80-ffffffff817ceaa8: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:285
Inline: False
```
**Symbols:**

```
ffffffff81c0082d-ffffffff81c00844: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff817b2490-ffffffff817b24b3: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:285
Inline: False
```
**Symbols:**

```
ffffffff81d02ff6-ffffffff81d03023: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff8183b880-ffffffff8183b8c2: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:285
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81ecb4cf-ffffffff81ecb4fd: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff8197cd80-ffffffff8197cdd5: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:290
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff82098405-ffffffff8209841a: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff81ae9fc0-ffffffff81aea032: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:288
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff82119437-ffffffff8211944c: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff81b38340-ffffffff81b383b2: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:288
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff821f73fa-ffffffff821f740f: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff81b8fde0-ffffffff81b8fe52: driver_deferred_probe_check_state (STB_GLOBAL)
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
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eac68)
Location: drivers/base/dd.c:262
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/iommu/of_iommu.c:of_iommu_xlate
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
```
**Symbols:**

```
ffff8000108eac68-ffff8000108eacd0: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8d9c)
Location: drivers/base/dd.c:262
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/iommu/of_iommu.c:of_iommu_xlate
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
```
**Symbols:**

```
c09d8d9c-c09d8e08: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000981fc0)
Location: drivers/base/dd.c:262
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/iommu/of_iommu.c:of_iommu_xlate
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
```
**Symbols:**

```
c000000000981fc0-c000000000982054: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057e9de)
Location: drivers/base/dd.c:262
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
```
**Symbols:**

```
ffffffe00057e9de-ffffffe00057ea3c: driver_deferred_probe_check_state (STB_GLOBAL)
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
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:262
Inline: False
```
**Symbols:**

```
ffffffff816c5c24-ffffffff816c5c3d: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff816c52b0-ffffffff816c52ed: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:262
Inline: False
```
**Symbols:**

```
ffffffff816a0ea4-ffffffff816a0ebd: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff816a0530-ffffffff816a056d: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:262
Inline: False
```
**Symbols:**

```
ffffffff816f40f4-ffffffff816f410d: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff816f3780-ffffffff816f37bd: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int driver_deferred_probe_check_state(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:262
Inline: False
```
**Symbols:**

```
ffffffff8170e920-ffffffff8170e939: driver_deferred_probe_check_state.cold (STB_LOCAL)
ffffffff8170dfb0-ffffffff8170dfed: driver_deferred_probe_check_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
