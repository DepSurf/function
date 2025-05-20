# Function: <code>devm_gpiod_get_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff814239c0)
Location: drivers/gpio/devres.c:99
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get
  - drivers/gpio/devres.c:devm_gpiod_get_optional
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffff814239c0-ffffffff81423a4d: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8146cfc0)
Location: drivers/gpio/devres.c:99
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
  - drivers/gpio/devres.c:devm_gpiod_get
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8146cfc0-ffffffff8146d057: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8148ee90)
Location: drivers/gpio/devres.c:99
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
  - drivers/gpio/devres.c:devm_gpiod_get
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8148ee90-ffffffff8148ef27: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81498930)
Location: drivers/gpio/devres.c:101
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
  - drivers/gpio/devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81498930-ffffffff814989cc: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff814d6c20)
Location: drivers/gpio/devres.c:101
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
  - drivers/gpio/devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff814d6c20-ffffffff814d6cbc: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81505d20)
Location: drivers/gpio/devres.c:101
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
  - drivers/gpio/devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81505d20-ffffffff81505db7: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81521020)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81521020-ffffffff815210e2: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8154f530)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8154f530-ffffffff8154f5f0: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81570af0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81570af0-ffffffff81570bb0: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81614fd0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81614fd0-ffffffff81615090: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff816392c0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff816392c0-ffffffff81639380: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8161cf20)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8161cf20-ffffffff8161cfe0: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c3a0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8168c3a0-ffffffff8168c467: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff817a98f0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff817a98f0-ffffffff817a99d3: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff818c23a0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff818c23a0-ffffffff818c2483: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff819052a0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff819052a0-ffffffff81905383: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8194ccb0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8194ccb0-ffffffff8194cd93: devm_gpiod_get_index (STB_GLOBAL)
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
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffff8000106c6a20)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffff8000106c6a20-ffff8000106c6b20: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c08644bc)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
c08644bc-c0864598: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c000000000843330)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
c000000000843330-c000000000843444: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aa612)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffe0004aa612-ffffffe0004aa6c6: devm_gpiod_get_index (STB_GLOBAL)
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
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff815662b0)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff815662b0-ffffffff81566370: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81557100)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
```
**Symbols:**

```
ffffffff81557100-ffffffff815571c0: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81564e20)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81564e20-ffffffff81564ee0: devm_gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8157ed40)
Location: drivers/gpio/gpiolib-devres.c:93
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8157ed40-ffffffff8157ee00: devm_gpiod_get_index (STB_GLOBAL)
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
