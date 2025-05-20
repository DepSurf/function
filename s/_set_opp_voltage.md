# Function: <code>_set_opp_voltage</code>

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
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3b20)
Location: drivers/opp/core.c:520
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff817d3b20-ffffffff817d3c20: _set_opp_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cd20)
Location: drivers/opp/core.c:527
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8181cd20-ffffffff8181ce28: _set_opp_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818488e0)
Location: drivers/opp/core.c:511
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818488e0-ffffffff818489e8: _set_opp_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:580
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8188b2c0-ffffffff8188b382: _set_opp_voltage (STB_LOCAL)
ffffffff8188d490-ffffffff8188d4be: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818bd3a0-ffffffff818bd462: _set_opp_voltage (STB_LOCAL)
ffffffff818bf6f0-ffffffff818bf71e: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
```
**Symbols:**

```
ffffffff8198da40-ffffffff8198db02: _set_opp_voltage (STB_LOCAL)
ffffffff81991170-ffffffff8199119e: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
```
**Symbols:**

```
ffffffff819915a0-ffffffff81991662: _set_opp_voltage (STB_LOCAL)
ffffffff81c28eb0-ffffffff81c28ede: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:707
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81975b70-ffffffff81975c32: _set_opp_voltage (STB_LOCAL)
ffffffff81c1b0b4-ffffffff81c1b0e2: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:707
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81a1e830-ffffffff81a1e8ec: _set_opp_voltage (STB_LOCAL)
ffffffff81d2b014-ffffffff81d2b042: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:852
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81b870f0-ffffffff81b871c4: _set_opp_voltage (STB_LOCAL)
ffffffff81ef71d2-ffffffff81ef7200: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d26ddd)
Location: drivers/opp/core.c:792
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_config_regulator_single
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d8ffdd)
Location: drivers/opp/core.c:795
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_config_regulator_single
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e4766d)
Location: drivers/opp/core.c:918
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_config_regulator_single
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
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b17df8)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffff800010b17df8-ffff800010b17f04: _set_opp_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf2e58)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
c0bf2e58-c0bf2f78: _set_opp_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09490)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
c000000000c09490-c000000000c09620: _set_opp_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000700c58)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffe000700c58-ffffffe000700d5e: _set_opp_voltage (STB_LOCAL)
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
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81861ac0-ffffffff81861b82: _set_opp_voltage (STB_LOCAL)
ffffffff81863e10-ffffffff81863e3e: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8182a770-ffffffff8182a832: _set_opp_voltage (STB_LOCAL)
ffffffff8182cac0-ffffffff8182caee: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818b2850-ffffffff818b2912: _set_opp_voltage (STB_LOCAL)
ffffffff818b4ba0-ffffffff818b4bce: _set_opp_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _set_opp_voltage(struct device *dev, struct regulator *reg, struct dev_pm_opp_supply *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:628
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818ceb00-ffffffff818cebc2: _set_opp_voltage (STB_LOCAL)
ffffffff818d0e50-ffffffff818d0e7e: _set_opp_voltage.cold (STB_LOCAL)
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
