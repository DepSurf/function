# Function: <code>lp_gpio_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a8d0)
Location: drivers/gpio/gpio-lynxpoint.c:113
Inline: True
```
**Symbols:**

```
ffffffff8142a8d0-ffffffff8142a97f: lp_gpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814754a0)
Location: drivers/gpio/gpio-lynxpoint.c:113
Inline: False
```
**Symbols:**

```
ffffffff814754a0-ffffffff8147557c: lp_gpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497a70)
Location: drivers/gpio/gpio-lynxpoint.c:113
Inline: False
```
**Symbols:**

```
ffffffff81497a70-ffffffff81497b4c: lp_gpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1720)
Location: drivers/gpio/gpio-lynxpoint.c:113
Inline: False
```
**Symbols:**

```
ffffffff814a1720-ffffffff814a17fc: lp_gpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e00f0)
Location: drivers/gpio/gpio-lynxpoint.c:113
Inline: False
```
**Symbols:**

```
ffffffff814e00f0-ffffffff814e01cc: lp_gpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f490)
Location: drivers/gpio/gpio-lynxpoint.c:113
Inline: False
```
**Symbols:**

```
ffffffff8150f490-ffffffff8150f56c: lp_gpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524b40)
Location: drivers/gpio/gpio-lynxpoint.c:99
Inline: False
```
**Symbols:**

```
ffffffff81524b40-ffffffff81524c1c: lp_gpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: drivers/gpio/gpio-lynxpoint.c:99
Inline: False
```
**Symbols:**

```
ffffffff81553220-ffffffff815532df: lp_gpio_request (STB_LOCAL)
ffffffff815534fb-ffffffff8155351f: lp_gpio_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: drivers/gpio/gpio-lynxpoint.c:99
Inline: False
```
**Symbols:**

```
ffffffff815748c0-ffffffff8157497f: lp_gpio_request (STB_LOCAL)
ffffffff81574b61-ffffffff81574b85: lp_gpio_request.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: drivers/gpio/gpio-lynxpoint.c:99
Inline: False
```
**Symbols:**

```
ffffffff8155aed0-ffffffff8155af8f: lp_gpio_request (STB_LOCAL)
ffffffff8155b171-ffffffff8155b195: lp_gpio_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: drivers/gpio/gpio-lynxpoint.c:99
Inline: False
```
**Symbols:**

```
ffffffff81568bf0-ffffffff81568caf: lp_gpio_request (STB_LOCAL)
ffffffff81568e91-ffffffff81568eb5: lp_gpio_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int lp_gpio_request(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: drivers/gpio/gpio-lynxpoint.c:99
Inline: False
```
**Symbols:**

```
ffffffff81582b10-ffffffff81582bcf: lp_gpio_request (STB_LOCAL)
ffffffff81582db1-ffffffff81582dd5: lp_gpio_request.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
