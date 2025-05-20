# Function: <code>__sx150x_gpio_set</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148ab03)
Location: drivers/pinctrl/pinctrl-sx150x.c:462
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814943df)
Location: drivers/pinctrl/pinctrl-sx150x.c:427
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d067f)
Location: drivers/pinctrl/pinctrl-sx150x.c:427
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501f93)
Location: drivers/pinctrl/pinctrl-sx150x.c:427
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81516a83)
Location: drivers/pinctrl/pinctrl-sx150x.c:427
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81544c2d)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81565b0d)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81608243)
Location: drivers/pinctrl/pinctrl-sx150x.c:422
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162ca40)
Location: drivers/pinctrl/pinctrl-sx150x.c:422
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8161071e)
Location: drivers/pinctrl/pinctrl-sx150x.c:422
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:422
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
ffffffff8167eaf0-ffffffff8167eb64: __sx150x_gpio_set (STB_LOCAL)
ffffffff81ce0c96-ffffffff81ce0cd1: __sx150x_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:422
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
ffffffff8179a5c0-ffffffff8179a63f: __sx150x_gpio_set (STB_LOCAL)
ffffffff81ea73b1-ffffffff81ea73e8: __sx150x_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:422
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
ffffffff818b0e60-ffffffff818b0edf: __sx150x_gpio_set (STB_LOCAL)
ffffffff8208e0cf-ffffffff8208e106: __sx150x_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:421
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
ffffffff818f3ee0-ffffffff818f3f5f: __sx150x_gpio_set (STB_LOCAL)
ffffffff8210e3a7-ffffffff8210e3de: __sx150x_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:420
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
ffffffff8193b710-ffffffff8193b78f: __sx150x_gpio_set (STB_LOCAL)
ffffffff821ebfe4-ffffffff821ec01b: __sx150x_gpio_set.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069e940)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (c0840fb8)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
c0840fb8-c0841010: __sx150x_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (c000000000836510)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
c000000000836510-c0000000008365a8: __sx150x_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sx150x_gpio_set(struct sx150x_pinctrl *pctl, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2542)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
**Symbols:**

```
ffffffe0004a2542-ffffffe0004a259a: __sx150x_gpio_set (STB_LOCAL)
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81559e3d)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81573ccd)
Location: drivers/pinctrl/pinctrl-sx150x.c:419
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
