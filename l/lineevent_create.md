# Function: <code>lineevent_create</code>

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
In drivers/gpio/gpiolib.c (ffffffff81471604)
Location: drivers/gpio/gpiolib.c:691
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff81493814)
Location: drivers/gpio/gpiolib.c:736
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff8149d164)
Location: drivers/gpio/gpiolib.c:737
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff814db784)
Location: drivers/gpio/gpiolib.c:775
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff815099f4)
Location: drivers/gpio/gpiolib.c:855
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff8151e2e4)
Location: drivers/gpio/gpiolib.c:879
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff8154c46e)
Location: drivers/gpio/gpiolib.c:887
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff8156d5e0)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lineevent_create(struct gpio_device *gdev, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81610bd0)
Location: drivers/gpio/gpiolib.c:1042
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81610bd0-ffffffff81610fb8: lineevent_create (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lineevent_create(struct gpio_device *gdev, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ad570)
Location: drivers/gpio/gpiolib-cdev.c:1898
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff817ad570-ffffffff817ad885: lineevent_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lineevent_create(struct gpio_device *gdev, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c6b50)
Location: drivers/gpio/gpiolib-cdev.c:2051
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff818c6b50-ffffffff818c6e7b: lineevent_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lineevent_create(struct gpio_device *gdev, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81909bf0)
Location: drivers/gpio/gpiolib-cdev.c:2049
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81909bf0-ffffffff81909f18: lineevent_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lineevent_create(struct gpio_device *gdev, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950fc0)
Location: drivers/gpio/gpiolib-cdev.c:2111
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81950fc0-ffffffff8195135f: lineevent_create (STB_LOCAL)
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
In drivers/gpio/gpiolib.c (ffff8000106c2e28)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0861368)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083f4a4)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a7d70)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562da0)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81553bf0)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561910)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
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
In drivers/gpio/gpiolib.c (ffffffff8157b800)
Location: drivers/gpio/gpiolib.c:890
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
