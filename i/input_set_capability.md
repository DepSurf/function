# Function: <code>input_set_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81669040)
Location: drivers/input/input.c:1909
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff81669040-ffffffff816690fd: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816c9950)
Location: drivers/input/input.c:1908
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff816c9950-ffffffff816c9a0d: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816f7930)
Location: drivers/input/input.c:1908
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff816f7930-ffffffff816f79ed: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8170d3e0)
Location: drivers/input/input.c:1908
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff8170d3e0-ffffffff8170d496: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8177e620)
Location: drivers/input/input.c:1902
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff8177e620-ffffffff8177e6db: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1910
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff817c01f3-ffffffff817c0214: input_set_capability.cold.22 (STB_LOCAL)
ffffffff817bf650-ffffffff817bf6f8: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817e6ab0)
Location: drivers/input/input.c:1910
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff817e6ab0-ffffffff817e6ba5: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff818280a4)
Location: drivers/input/input.c:1906
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff818280a4-ffffffff818280c5: input_set_capability.cold (STB_LOCAL)
ffffffff81826db0-ffffffff81826e98: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff8185960e)
Location: drivers/input/input.c:1979
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff8185960e-ffffffff8185962f: input_set_capability.cold (STB_LOCAL)
ffffffff818582e0-ffffffff818583c8: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1977
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff8192c2ea-ffffffff8192c30b: input_set_capability.cold (STB_LOCAL)
ffffffff81929e40-ffffffff81929f26: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2075
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff81c232ff-ffffffff81c23320: input_set_capability.cold (STB_LOCAL)
ffffffff819313b0-ffffffff81931496: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2075
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff81c153f5-ffffffff81c15416: input_set_capability.cold (STB_LOCAL)
ffffffff819146c0-ffffffff819147aa: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2075
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff81d2327a-ffffffff81d2329b: input_set_capability.cold (STB_LOCAL)
ffffffff819b6850-ffffffff819b693a: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81b16d08)
Location: drivers/input/input.c:2120
Inline: True
Inline callers:
  - drivers/input/input.c:input_copy_abs
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff81eef058-ffffffff81eef098: input_set_capability.cold (STB_LOCAL)
ffffffff81b16580-ffffffff81b166fd: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81ca7060)
Location: drivers/input/input.c:2104
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/input.c:input_copy_abs
```
**Symbols:**

```
ffffffff81ca7060-ffffffff81ca722c: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d0ecd0)
Location: drivers/input/input.c:2103
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/input.c:input_copy_abs
```
**Symbols:**

```
ffffffff81d0ecd0-ffffffff81d0ee94: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc49f0)
Location: drivers/input/input.c:2103
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/input.c:input_copy_abs
```
**Symbols:**

```
ffffffff81dc49f0-ffffffff81dc4bb4: input_set_capability (STB_GLOBAL)
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
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a97d28)
Location: drivers/input/input.c:1979
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffff800010a97d28-ffff800010a97eec: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b7a428)
Location: drivers/input/input.c:1979
Inline: False
Direct callers:
  - sound/core/jack.c:snd_jack_new
  - sound/core/jack.c:snd_jack_dev_register
```
**Symbols:**

```
c0b7a428-c0b7a5a4: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b77a80)
Location: drivers/input/input.c:1979
Inline: False
```
**Symbols:**

```
c000000000b77a80-c000000000b77cb8: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a98b4)
Location: drivers/input/input.c:1979
Inline: False
```
**Symbols:**

```
ffffffe0006a98b4-ffffffe0006a9a3e: input_set_capability (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff8180e61e)
Location: drivers/input/input.c:1979
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff8180e61e-ffffffff8180e63f: input_set_capability.cold (STB_LOCAL)
ffffffff8180d2f0-ffffffff8180d3d8: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff817d5d6e)
Location: drivers/input/input.c:1979
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff817d5d6e-ffffffff817d5d8f: input_set_capability.cold (STB_LOCAL)
ffffffff817d4a60-ffffffff817d4b48: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff8184d79e)
Location: drivers/input/input.c:1979
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff8184d79e-ffffffff8184d7bf: input_set_capability.cold (STB_LOCAL)
ffffffff8184c470-ffffffff8184c558: input_set_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void input_set_capability(struct input_dev *dev, unsigned int type, unsigned int code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81868978)
Location: drivers/input/input.c:1979
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff81868978-ffffffff81868999: input_set_capability.cold (STB_LOCAL)
ffffffff818676d0-ffffffff818677b8: input_set_capability (STB_GLOBAL)
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
