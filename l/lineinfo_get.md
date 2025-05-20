# Function: <code>lineinfo_get</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lineinfo_get(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a000)
Location: drivers/gpio/gpiolib-cdev.c:2050
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff8163a000-ffffffff8163a134: lineinfo_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lineinfo_get(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dc50)
Location: drivers/gpio/gpiolib-cdev.c:2051
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff8161dc50-ffffffff8161dd84: lineinfo_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lineinfo_get(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d270)
Location: drivers/gpio/gpiolib-cdev.c:2051
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff8168d270-ffffffff8168d3a4: lineinfo_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lineinfo_get(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abe00)
Location: drivers/gpio/gpiolib-cdev.c:2244
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff817abe00-ffffffff817abf61: lineinfo_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lineinfo_get(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4740)
Location: drivers/gpio/gpiolib-cdev.c:2398
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff818c4740-ffffffff818c48a1: lineinfo_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lineinfo_get(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907810)
Location: drivers/gpio/gpiolib-cdev.c:2395
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81907810-ffffffff81907971: lineinfo_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lineinfo_get(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950c90)
Location: drivers/gpio/gpiolib-cdev.c:2450
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81950c90-ffffffff81950e1d: lineinfo_get (STB_LOCAL)
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
