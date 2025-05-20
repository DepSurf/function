# Function: <code>stmpe_enable</code>

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
int stmpe_enable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092e910)
Location: drivers/mfd/stmpe.c:132
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
**Symbols:**

```
ffff80001092e910-ffff80001092e974: stmpe_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stmpe_enable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a10184)
Location: drivers/mfd/stmpe.c:132
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
**Symbols:**

```
c0a10184-c0a101d8: stmpe_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stmpe_enable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009ce210)
Location: drivers/mfd/stmpe.c:132
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
**Symbols:**

```
c0000000009ce210-c0000000009ce29c: stmpe_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stmpe_enable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a5488)
Location: drivers/mfd/stmpe.c:132
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
**Symbols:**

```
ffffffe0005a5488-ffffffe0005a54da: stmpe_enable (STB_GLOBAL)
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
