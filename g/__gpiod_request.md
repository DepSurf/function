# Function: <code>__gpiod_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81424050)
Location: drivers/gpio/gpiolib.c:891
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff81424050-ffffffff81424145: __gpiod_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146d6d0)
Location: drivers/gpio/gpiolib.c:1815
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff8146d6d0-ffffffff8146d7b9: __gpiod_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148f5a0)
Location: drivers/gpio/gpiolib.c:2002
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff8148f5a0-ffffffff8148f689: __gpiod_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a1e0)
Location: drivers/gpio/gpiolib.c:2003
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff8149a1e0-ffffffff8149a2d0: __gpiod_request (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
