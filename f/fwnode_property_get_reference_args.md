# Function: <code>fwnode_property_get_reference_args</code>

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
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d120)
Location: drivers/base/property.c:691
Inline: False
```
**Symbols:**

```
ffffffff8164d120-ffffffff8164d153: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688a40)
Location: drivers/base/property.c:752
Inline: False
```
**Symbols:**

```
ffffffff81688a40-ffffffff81688a73: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8730)
Location: drivers/base/property.c:477
Inline: False
```
**Symbols:**

```
ffffffff816a8730-ffffffff816a8763: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e17fc)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffffffff816e17a0-ffffffff816e17d3: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817059ac)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffffffff81705950-ffffffff81705983: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0b5c)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff817c01c0-ffffffff817c01f3: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d65d1)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff817d5080-ffffffff817d50b3: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817ba0b9)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff817b8a90-ffffffff817b8ac3: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843d82)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff81842720-ffffffff81842753: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819865f0)
Location: drivers/base/property.c:511
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff819865f0-ffffffff819866ce: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4c90)
Location: drivers/base/property.c:519
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_gpio_count
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81af4c90-ffffffff81af4d6e: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42ea0)
Location: drivers/base/property.c:523
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_gpio_count
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81b42ea0-ffffffff81b42f7e: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9ad70)
Location: drivers/base/property.c:559
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_gpio_count
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81b9ad70-ffffffff81b9ae4e: fwnode_property_get_reference_args (STB_GLOBAL)
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
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f23bc)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffff8000108f2300-ffff8000108f2388: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df004)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
c09def70-c09defd4: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098bca4)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
c00000000098bc10-c00000000098bc80: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000583fac)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffffffe000583f2c-ffffffe000583f8e: fwnode_property_get_reference_args (STB_GLOBAL)
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
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb0fc)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffffffff816cb0a0-ffffffff816cb0d3: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a642c)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffffffff816a63d0-ffffffff816a6403: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f966c)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffffffff816f9610-ffffffff816f9643: fwnode_property_get_reference_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_get_reference_args(const struct fwnode_handle *fwnode, const char *prop, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81713f0c)
Location: drivers/base/property.c:477
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_find_reference
```
**Symbols:**

```
ffffffff81713eb0-ffffffff81713ee3: fwnode_property_get_reference_args (STB_GLOBAL)
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
