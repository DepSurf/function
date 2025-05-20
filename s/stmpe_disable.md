# Function: <code>stmpe_disable</code>

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
int stmpe_disable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092e978)
Location: drivers/mfd/stmpe.c:149
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
**Symbols:**

```
ffff80001092e978-ffff80001092e9dc: stmpe_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stmpe_disable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a101d8)
Location: drivers/mfd/stmpe.c:149
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
**Symbols:**

```
c0a101d8-c0a1022c: stmpe_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stmpe_disable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009ce2a0)
Location: drivers/mfd/stmpe.c:149
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
**Symbols:**

```
c0000000009ce2a0-c0000000009ce32c: stmpe_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stmpe_disable(struct stmpe *stmpe, unsigned int blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a54da)
Location: drivers/mfd/stmpe.c:149
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
**Symbols:**

```
ffffffe0005a54da-ffffffe0005a552c: stmpe_disable (STB_GLOBAL)
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
