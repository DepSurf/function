# Function: <code>tps68470_gpio_set</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff814e0de0)
Location: drivers/gpio/gpio-tps68470.c:81
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff814e0de0-ffffffff814e0e39: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff815105d0)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff815105d0-ffffffff81510629: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff81525c80)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81525c80-ffffffff81525cd9: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff81554340)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81554340-ffffffff81554397: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff81575990)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81575990-ffffffff815759e7: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff8161a460)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff8161a460-ffffffff8161a4b7: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff81640d50)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81640d50-ffffffff81640da7: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff81624300)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81624300-ffffffff81624359: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (0)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81693b00-ffffffff81693b87: tps68470_gpio_set (STB_LOCAL)
ffffffff81ce2b95-ffffffff81ce2bd6: tps68470_gpio_set.cold (STB_LOCAL)
```
</details>
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
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffff8000106d60d0)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffff8000106d60d0-ffff8000106d6144: tps68470_gpio_set (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff81569cc0)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81569cc0-ffffffff81569d17: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tps68470_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps68470.c (ffffffff81583be0)
Location: drivers/gpio/gpio-tps68470.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
```
**Symbols:**

```
ffffffff81583be0-ffffffff81583c37: tps68470_gpio_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
