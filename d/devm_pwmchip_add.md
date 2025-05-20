# Function: <code>devm_pwmchip_add</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int devm_pwmchip_add(struct device *dev, struct pwm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81694c30)
Location: drivers/pwm/core.c:331
Inline: True
Direct callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
**Symbols:**

```
ffffffff81694c30-ffffffff81694c8b: devm_pwmchip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int devm_pwmchip_add(struct device *dev, struct pwm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b5770)
Location: drivers/pwm/core.c:357
Inline: True
Direct callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
**Symbols:**

```
ffffffff817b5770-ffffffff817b57dc: devm_pwmchip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int devm_pwmchip_add(struct device *dev, struct pwm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cfb10)
Location: drivers/pwm/core.c:353
Inline: True
Direct callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
**Symbols:**

```
ffffffff818cfb10-ffffffff818cfb7c: devm_pwmchip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int devm_pwmchip_add(struct device *dev, struct pwm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81912870)
Location: drivers/pwm/core.c:344
Inline: True
Direct callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
**Symbols:**

```
ffffffff81912870-ffffffff819128e7: devm_pwmchip_add (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
