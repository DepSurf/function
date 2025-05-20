# Function: <code>stmpe_24xx_pwm_enable</code>

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
int stmpe_24xx_pwm_enable(struct pwm_chip *chip, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (ffff8000106d9f70)
Location: drivers/pwm/pwm-stmpe.c:39
Inline: False
Direct callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
**Symbols:**

```
ffff8000106d9f70-ffff8000106da00c: stmpe_24xx_pwm_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stmpe_24xx_pwm_enable(struct pwm_chip *chip, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (c0876794)
Location: drivers/pwm/pwm-stmpe.c:39
Inline: False
Direct callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
**Symbols:**

```
c0876794-c087681c: stmpe_24xx_pwm_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stmpe_24xx_pwm_enable(struct pwm_chip *chip, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (c000000000851ab0)
Location: drivers/pwm/pwm-stmpe.c:39
Inline: False
Direct callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
**Symbols:**

```
c000000000851ab0-c000000000851b80: stmpe_24xx_pwm_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stmpe_24xx_pwm_enable(struct pwm_chip *chip, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-stmpe.c (ffffffe0004b31c4)
Location: drivers/pwm/pwm-stmpe.c:39
Inline: False
Direct callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
```
**Symbols:**

```
ffffffe0004b31c4-ffffffe0004b325e: stmpe_24xx_pwm_enable (STB_LOCAL)
```
</details>
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
