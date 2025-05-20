# Function: <code>gpio_set_open_drain_value_commit</code>

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
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9a90)
Location: drivers/gpio/gpiolib.c:2757
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff814d9a90-ffffffff814d9bd0: gpio_set_open_drain_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2933
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81508990-ffffffff81508a83: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff8150bded-ffffffff8150be33: gpio_set_open_drain_value_commit.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3060
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8151d160-ffffffff8151d253: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81520cc3-ffffffff81520d09: gpio_set_open_drain_value_commit.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3148
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8154b260-ffffffff8154b344: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff8154efcd-ffffffff8154f011: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8156c440-ffffffff8156c521: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81570575-ffffffff815705b9: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3914
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff816101c0-ffffffff816102a2: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff8161463e-ffffffff81614682: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff816362c0-ffffffff8163638c: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81bf5e4d-ffffffff81bf5e97: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2716
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff816199f0-ffffffff81619ab4: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81be7c70-ffffffff81be7cba: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2756
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81688e10-ffffffff81688ed1: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81ce17fa-ffffffff81ce1844: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff817a5bf0-ffffffff817a5cde: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81ea8077-ffffffff81ea80c1: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd9b0)
Location: drivers/gpio/gpiolib.c:2947
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff818bd9b0-ffffffff818bdaf2: gpio_set_open_drain_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900be0)
Location: drivers/gpio/gpiolib.c:2988
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81900be0-ffffffff81900d22: gpio_set_open_drain_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81948410)
Location: drivers/gpio/gpiolib.c:3181
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81948410-ffffffff81948537: gpio_set_open_drain_value_commit (STB_LOCAL)
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
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c2080)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffff8000106c2080-ffff8000106c21ec: gpio_set_open_drain_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085fe78)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
c085fe78-c085ffcc: gpio_set_open_drain_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083d470)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
c00000000083d470-c00000000083d62c: gpio_set_open_drain_value_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6c5c)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffe0004a6c5c-ffffffe0004a6d7e: gpio_set_open_drain_value_commit (STB_LOCAL)
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
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81561c00-ffffffff81561ce1: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81565d35-ffffffff81565d79: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81552a50-ffffffff81552b31: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff81556b85-ffffffff81556bc9: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff81560770-ffffffff81560851: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff815648a5-ffffffff815648e9: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_nocheck
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
**Symbols:**

```
ffffffff8157a5e0-ffffffff8157a6dd: gpio_set_open_drain_value_commit (STB_LOCAL)
ffffffff8157e7c5-ffffffff8157e809: gpio_set_open_drain_value_commit.cold (STB_LOCAL)
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
