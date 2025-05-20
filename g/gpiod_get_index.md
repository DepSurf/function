# Function: <code>gpiod_get_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426dc0)
Location: drivers/gpio/gpiolib.c:2128
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
**Symbols:**

```
ffffffff81426dc0-ffffffff8142715e: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81471ac0)
Location: drivers/gpio/gpiolib.c:3136
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
```
**Symbols:**

```
ffffffff81471ac0-ffffffff81471eb6: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81493d50)
Location: drivers/gpio/gpiolib.c:3257
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
```
**Symbols:**

```
ffffffff81493d50-ffffffff81493fd7: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149dcb0)
Location: drivers/gpio/gpiolib.c:3268
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
```
**Symbols:**

```
ffffffff8149dcb0-ffffffff8149df65: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dc800)
Location: drivers/gpio/gpiolib.c:3614
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
```
**Symbols:**

```
ffffffff814dc800-ffffffff814dcab2: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150abe0)
Location: drivers/gpio/gpiolib.c:3834
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
```
**Symbols:**

```
ffffffff8150abe0-ffffffff8150aec0: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151f750)
Location: drivers/gpio/gpiolib.c:4094
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff8151f750-ffffffff8151fa5f: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4193
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff8154f261-ffffffff8154f2b7: gpiod_get_index.cold (STB_LOCAL)
ffffffff8154d8f0-ffffffff8154dbb5: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff8157075e-ffffffff815707bf: gpiod_get_index.cold (STB_LOCAL)
ffffffff8156eaf0-ffffffff8156edb5: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:5000
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81614d48-ffffffff81614d5f: gpiod_get_index.cold (STB_LOCAL)
ffffffff81613030-ffffffff816132a3: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3824
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81bf65da-ffffffff81bf65f1: gpiod_get_index.cold (STB_LOCAL)
ffffffff81637ef0-ffffffff8163816f: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3806
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81be8480-ffffffff81be84de: gpiod_get_index.cold (STB_LOCAL)
ffffffff8161b8a0-ffffffff8161bca6: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3865
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81ce212d-ffffffff81ce218b: gpiod_get_index.cold (STB_LOCAL)
ffffffff8168adb0-ffffffff8168b1b3: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3993
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81ea8b40-ffffffff81ea8b9b: gpiod_get_index.cold (STB_LOCAL)
ffffffff817a80f0-ffffffff817a852c: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c11d4)
Location: drivers/gpio/gpiolib.c:4144
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff818c0d30-ffffffff818c0dab: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81904177)
Location: drivers/gpio/gpiolib.c:4182
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81903d00-ffffffff81903d7b: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194bba9)
Location: drivers/gpio/gpiolib.c:4381
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff8194b740-ffffffff8194b7bb: gpiod_get_index (STB_GLOBAL)
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
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c4900)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffff8000106c4900-ffff8000106c4c70: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0862b80)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
```
**Symbols:**

```
c0862b80-c0862ee4: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0000000008411a0)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
c0000000008411a0-c00000000084177c: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a9064)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffe0004a9064-ffffffe0004a9308: gpiod_get_index (STB_GLOBAL)
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
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81565f1e-ffffffff81565f7f: gpiod_get_index.cold (STB_LOCAL)
ffffffff815642b0-ffffffff81564575: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81556d6e-ffffffff81556dcf: gpiod_get_index.cold (STB_LOCAL)
ffffffff81555100-ffffffff815553c5: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff81564a8e-ffffffff81564aef: gpiod_get_index.cold (STB_LOCAL)
ffffffff81562e20-ffffffff815630e5: gpiod_get_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiod_get_index(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4527
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
**Symbols:**

```
ffffffff8157e9ae-ffffffff8157ea0f: gpiod_get_index.cold (STB_LOCAL)
ffffffff8157cd40-ffffffff8157d005: gpiod_get_index (STB_GLOBAL)
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
