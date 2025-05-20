# Function: <code>berlin_pinctrl_probe_regmap</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int berlin_pinctrl_probe_regmap(struct platform_device *pdev, const struct berlin_pinctrl_desc *desc, struct regmap *regmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/berlin/berlin.c (ffff8000106a7c48)
Location: drivers/pinctrl/berlin/berlin.c:294
Inline: False
Direct callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
```
**Symbols:**

```
ffff8000106a7c48-ffff8000106a7f28: berlin_pinctrl_probe_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int berlin_pinctrl_probe_regmap(struct platform_device *pdev, const struct berlin_pinctrl_desc *desc, struct regmap *regmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/berlin/berlin.c (c0847c90)
Location: drivers/pinctrl/berlin/berlin.c:294
Inline: False
Direct callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
```
**Symbols:**

```
c0847c90-c0847f88: berlin_pinctrl_probe_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
