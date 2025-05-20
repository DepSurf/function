# Function: <code>lineinfo_get_v1</code>

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
int lineinfo_get_v1(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ab8a0)
Location: drivers/gpio/gpiolib-cdev.c:2208
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff817ab8a0-ffffffff817aba12: lineinfo_get_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lineinfo_get_v1(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5900)
Location: drivers/gpio/gpiolib-cdev.c:2362
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff818c5900-ffffffff818c5a72: lineinfo_get_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lineinfo_get_v1(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff819089b0)
Location: drivers/gpio/gpiolib-cdev.c:2359
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff819089b0-ffffffff81908b22: lineinfo_get_v1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lineinfo_get_v1(struct gpio_chardev_data *cdev, void *ip, bool watch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950e30)
Location: drivers/gpio/gpiolib-cdev.c:2414
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81950e30-ffffffff81950fa2: lineinfo_get_v1 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
