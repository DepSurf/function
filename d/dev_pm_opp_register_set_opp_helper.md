# Function: <code>dev_pm_opp_register_set_opp_helper</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d5590)
Location: drivers/opp/core.c:1516
Inline: True
```
**Symbols:**

```
ffffffff817d5590-ffffffff817d55f7: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181e2f0)
Location: drivers/opp/core.c:1499
Inline: True
```
**Symbols:**

```
ffffffff8181e2f0-ffffffff8181e355: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8184a050)
Location: drivers/opp/core.c:1640
Inline: True
```
**Symbols:**

```
ffffffff8184a050-ffffffff8184a0b5: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188ce0b)
Location: drivers/opp/core.c:1711
Inline: True
```
**Symbols:**

```
ffffffff8188d8c4-ffffffff8188d8e6: dev_pm_opp_register_set_opp_helper.cold (STB_LOCAL)
ffffffff8188cdf0-ffffffff8188ce5c: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bef90)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
ffffffff818bef90-ffffffff818beff5: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81990560)
Location: drivers/opp/core.c:1874
Inline: True
```
**Symbols:**

```
ffffffff81990560-ffffffff8199062f: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819944b0)
Location: drivers/opp/core.c:1968
Inline: True
```
**Symbols:**

```
ffffffff819944b0-ffffffff81994545: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81978a55)
Location: drivers/opp/core.c:2206
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
```
**Symbols:**

```
ffffffff81978920-ffffffff81978a25: dev_pm_opp_register_set_opp_helper.part.0 (STB_LOCAL)
ffffffff81978a30-ffffffff81978a4d: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81a219d5)
Location: drivers/opp/core.c:2216
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
```
**Symbols:**

```
ffffffff81a218a0-ffffffff81a219a5: dev_pm_opp_register_set_opp_helper.part.0 (STB_LOCAL)
ffffffff81a219b0-ffffffff81a219cd: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8a9f5)
Location: drivers/opp/core.c:2356
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
```
**Symbols:**

```
ffffffff81b8a8b0-ffffffff81b8a9be: dev_pm_opp_register_set_opp_helper.part.0 (STB_LOCAL)
ffffffff81b8a9c0-ffffffff81b8a9ed: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a1a0)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
ffff800010b1a1a0-ffff800010b1a238: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4e0c)
Location: drivers/opp/core.c:1760
Inline: True
Direct callers:
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_probe
```
**Symbols:**

```
c0bf4e0c-c0bf4e8c: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0bdd0)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
c000000000c0bdd0-c000000000c0bea0: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702986)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
ffffffe000702986-ffffffe000702a02: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818636b0)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
ffffffff818636b0-ffffffff81863715: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182c360)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
ffffffff8182c360-ffffffff8182c3c5: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4440)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
ffffffff818b4440-ffffffff818b44a5: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *dev_pm_opp_register_set_opp_helper(struct device *dev, int (*set_opp)(struct dev_pm_set_opp_data *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d06f0)
Location: drivers/opp/core.c:1760
Inline: True
```
**Symbols:**

```
ffffffff818d06f0-ffffffff818d0755: dev_pm_opp_register_set_opp_helper (STB_GLOBAL)
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
