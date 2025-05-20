# Function: <code>devm_gpiod_unhinge</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81521680)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffff81521680-ffffffff815216c4: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8154fbdd)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffff8154fbdd-ffffffff8154fbf0: devm_gpiod_unhinge.cold (STB_LOCAL)
ffffffff8154fb60-ffffffff8154fba4: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81571050)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffff81571050-ffffffff81571094: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81615530)
Location: drivers/gpio/gpiolib-devres.c:344
Inline: True
```
**Symbols:**

```
ffffffff81615530-ffffffff81615574: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81639770)
Location: drivers/gpio/gpiolib-devres.c:342
Inline: True
```
**Symbols:**

```
ffffffff81639770-ffffffff816397b4: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8161d3c0)
Location: drivers/gpio/gpiolib-devres.c:342
Inline: True
```
**Symbols:**

```
ffffffff8161d3c0-ffffffff8161d404: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c710)
Location: drivers/gpio/gpiolib-devres.c:342
Inline: False
```
**Symbols:**

```
ffffffff8168c710-ffffffff8168c754: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff817a9cd0)
Location: drivers/gpio/gpiolib-devres.c:342
Inline: False
```
**Symbols:**

```
ffffffff817a9cd0-ffffffff817a9d30: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff818c27c0)
Location: drivers/gpio/gpiolib-devres.c:342
Inline: False
```
**Symbols:**

```
ffffffff818c27c0-ffffffff818c2820: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff819056c0)
Location: drivers/gpio/gpiolib-devres.c:287
Inline: False
```
**Symbols:**

```
ffffffff819056c0-ffffffff81905720: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8194d0d0)
Location: drivers/gpio/gpiolib-devres.c:287
Inline: False
```
**Symbols:**

```
ffffffff8194d0d0-ffffffff8194d130: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffff8000106c7248)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffff8000106c7248-ffff8000106c72b0: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c0864bec)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
c0864bec-c0864c60: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c000000000843b00)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: False
```
**Symbols:**

```
c000000000843b00-c000000000843b90: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aac88)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffe0004aac88-ffffffe0004aace0: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81566810)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffff81566810-ffffffff81566854: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81557660)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffff81557660-ffffffff815576a4: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81565380)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffff81565380-ffffffff815653c4: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_gpiod_unhinge(struct device *dev, struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8157f2a0)
Location: drivers/gpio/gpiolib-devres.c:359
Inline: True
```
**Symbols:**

```
ffffffff8157f2a0-ffffffff8157f2e4: devm_gpiod_unhinge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
