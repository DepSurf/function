# Function: <code>palmas_gpio_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:69
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:69
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:69
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:69
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (ffffffff8150fce0)
Location: drivers/gpio/gpio-palmas.c:69
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff8150fce0-ffffffff8150fd69: palmas_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (ffffffff81525390)
Location: drivers/gpio/gpio-palmas.c:69
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81525390-ffffffff81525419: palmas_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81553690-ffffffff81553705: palmas_gpio_set (STB_LOCAL)
ffffffff81553999-ffffffff815539b3: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81574ce0-ffffffff81574d55: palmas_gpio_set (STB_LOCAL)
ffffffff81574fe9-ffffffff81575003: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81619770-ffffffff816197e5: palmas_gpio_set (STB_LOCAL)
ffffffff81619a75-ffffffff81619a8f: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff8163ff50-ffffffff8163ffc5: palmas_gpio_set (STB_LOCAL)
ffffffff81bf6af4-ffffffff81bf6b0e: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81623520-ffffffff81623594: palmas_gpio_set (STB_LOCAL)
ffffffff81be89be-ffffffff81be89d8: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81692cd0-ffffffff81692d44: palmas_gpio_set (STB_LOCAL)
ffffffff81ce28ff-ffffffff81ce2919: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff817b3810-ffffffff817b388e: palmas_gpio_set (STB_LOCAL)
ffffffff81ea9461-ffffffff81ea947a: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (ffffffff818cd8f0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff818cd8f0-ffffffff818cd993: palmas_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (ffffffff81910950)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81910950-ffffffff819109f3: palmas_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (ffffffff81958820)
Location: drivers/gpio/gpio-palmas.c:57
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81958820-ffffffff819588c3: palmas_gpio_set (STB_LOCAL)
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
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (ffff8000106d2cd8)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffff8000106d2cd8-ffff8000106d2d90: palmas_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (c086e59c)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
c086e59c-c086e630: palmas_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (c00000000084a750)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
c00000000084a750-c00000000084a838: palmas_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-palmas.c (ffffffe0004aecec)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffe0004aecec-ffffffe0004aed84: palmas_gpio_set (STB_LOCAL)
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81569010-ffffffff81569085: palmas_gpio_set (STB_LOCAL)
ffffffff81569319-ffffffff81569333: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void palmas_gpio_set(struct gpio_chip *gc, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-palmas.c (0)
Location: drivers/gpio/gpio-palmas.c:58
Inline: False
Direct callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
**Symbols:**

```
ffffffff81582f30-ffffffff81582fa5: palmas_gpio_set (STB_LOCAL)
ffffffff81583239-ffffffff81583253: palmas_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
