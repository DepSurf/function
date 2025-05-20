# Function: <code>stmpe_reg_read</code>

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
int stmpe_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092ea50)
Location: drivers/mfd/stmpe.c:166
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_enable
```
**Symbols:**

```
ffff80001092ea50-ffff80001092eaa8: stmpe_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stmpe_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a10280)
Location: drivers/mfd/stmpe.c:166
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_enable
```
**Symbols:**

```
c0a10280-c0a102c8: stmpe_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stmpe_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009ce3d0)
Location: drivers/mfd/stmpe.c:166
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_enable
```
**Symbols:**

```
c0000000009ce3d0-c0000000009ce444: stmpe_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stmpe_reg_read(struct stmpe *stmpe, u8 reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a5580)
Location: drivers/mfd/stmpe.c:166
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_enable
```
**Symbols:**

```
ffffffe0005a5580-ffffffe0005a55d2: stmpe_reg_read (STB_GLOBAL)
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
