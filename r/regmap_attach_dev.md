# Function: <code>regmap_attach_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815624e0)
Location: drivers/base/regmap/regmap.c:434
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff815624e0-ffffffff81562545: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b6e30)
Location: drivers/base/regmap/regmap.c:492
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff815b6e30-ffffffff815b6e95: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e6150)
Location: drivers/base/regmap/regmap.c:515
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff815e6150-ffffffff815e61b5: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fab30)
Location: drivers/base/regmap/regmap.c:515
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff815fab30-ffffffff815fab95: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81662ce0)
Location: drivers/base/regmap/regmap.c:561
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81662ce0-ffffffff81662d45: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8169e510)
Location: drivers/base/regmap/regmap.c:564
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8169e510-ffffffff8169e575: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816bec80)
Location: drivers/base/regmap/regmap.c:596
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816bec80-ffffffff816bece5: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816f9db0)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816f9db0-ffffffff816f9e17: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8171e160)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8171e160-ffffffff8171e1c7: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817dc541)
Location: drivers/base/regmap/regmap.c:584
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff817da280-ffffffff817da2e7: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817ef6a0)
Location: drivers/base/regmap/regmap.c:611
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff817ef6a0-ffffffff817ef73c: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d3f40)
Location: drivers/base/regmap/regmap.c:611
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff817d3f40-ffffffff817d3fdc: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8185f1b0)
Location: drivers/base/regmap/regmap.c:638
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8185f1b0-ffffffff8185f25b: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819a75a0)
Location: drivers/base/regmap/regmap.c:638
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff819a75a0-ffffffff819a7651: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1a760)
Location: drivers/base/regmap/regmap.c:627
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81b1a760-ffffffff81b1a811: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b69370)
Location: drivers/base/regmap/regmap.c:627
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81b69370-ffffffff81b69421: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bbcef0)
Location: drivers/base/regmap/regmap.c:573
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81bbcef0-ffffffff81bbcfa1: regmap_attach_dev (STB_GLOBAL)
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
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010912230)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/reset/reset-imx7.c:imx7_reset_probe
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffff800010912230-ffff8000109122b4: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09f8350)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/reset/reset-imx7.c:imx7_reset_probe
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
c09f8350-c09f83c0: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b3840)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
c0000000009b3840-c0000000009b38e4: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000593e72)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffe000593e72-ffffffe000593eea: regmap_attach_dev (STB_GLOBAL)
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
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e4490)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816e4490-ffffffff816e44f7: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816bead0)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816bead0-ffffffff816beb37: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81711620)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81711620-ffffffff81711687: regmap_attach_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_attach_dev(struct device *dev, struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172c780)
Location: drivers/base/regmap/regmap.c:592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8172c780-ffffffff8172c7e7: regmap_attach_dev (STB_GLOBAL)
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
