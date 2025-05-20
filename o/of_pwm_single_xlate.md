# Function: <code>of_pwm_single_xlate</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_single_xlate(struct pwm_chip *pc, const struct of_phandle_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b5800)
Location: drivers/pwm/core.c:156
Inline: True
```
**Symbols:**

```
ffffffff817b5800-ffffffff817b58d2: of_pwm_single_xlate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_single_xlate(struct pwm_chip *pc, const struct of_phandle_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cfb90)
Location: drivers/pwm/core.c:168
Inline: True
```
**Symbols:**

```
ffffffff818cfb90-ffffffff818cfc62: of_pwm_single_xlate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_single_xlate(struct pwm_chip *pc, const struct of_phandle_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81912b10)
Location: drivers/pwm/core.c:161
Inline: True
```
**Symbols:**

```
ffffffff81912b10-ffffffff81912be2: of_pwm_single_xlate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_single_xlate(struct pwm_chip *chip, const struct of_phandle_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8195aa40)
Location: drivers/pwm/core.c:137
Inline: True
```
**Symbols:**

```
ffffffff8195aa40-ffffffff8195ab12: of_pwm_single_xlate (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pwm_chip *chip</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pwm_chip *pc</code>
</li>
</ul>
</details>
</li>
</ul>
