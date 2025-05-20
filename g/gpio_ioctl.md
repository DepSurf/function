# Function: <code>gpio_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81471590)
Location: drivers/gpio/gpiolib.c:810
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff81471590-ffffffff81471a3d: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814937a0)
Location: drivers/gpio/gpiolib.c:883
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff814937a0-ffffffff81493cc7: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149d0f0)
Location: drivers/gpio/gpiolib.c:884
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8149d0f0-ffffffff8149d619: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814db710)
Location: drivers/gpio/gpiolib.c:922
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff814db710-ffffffff814dbc39: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509980)
Location: drivers/gpio/gpiolib.c:1002
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff81509980-ffffffff81509ec8: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151e270)
Location: drivers/gpio/gpiolib.c:1025
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8151e270-ffffffff8151e7b2: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154c400)
Location: drivers/gpio/gpiolib.c:1033
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8154c400-ffffffff8154c965: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156d570)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8156d570-ffffffff8156db51: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81611cc0)
Location: drivers/gpio/gpiolib.c:1271
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff81611cc0-ffffffff81611fec: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b4a0)
Location: drivers/gpio/gpiolib-cdev.c:2104
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8163b4a0-ffffffff8163b5ad: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int gpio_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:2105
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8161eb00-ffffffff8161ed0a: gpio_ioctl (STB_LOCAL)
ffffffff81be8743-ffffffff81be875b: gpio_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int gpio_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:2105
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8168e430-ffffffff8168e63a: gpio_ioctl (STB_LOCAL)
ffffffff81ce2491-ffffffff81ce24a9: gpio_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817add60)
Location: drivers/gpio/gpiolib-cdev.c:2298
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff817add60-ffffffff817adefe: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c7370)
Location: drivers/gpio/gpiolib-cdev.c:2452
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff818c7370-ffffffff818c750e: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190a410)
Location: drivers/gpio/gpiolib-cdev.c:2449
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8190a410-ffffffff8190a5a7: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951ef0)
Location: drivers/gpio/gpiolib-cdev.c:2505
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff81951ef0-ffffffff81952100: gpio_ioctl (STB_LOCAL)
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
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c2da0)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffff8000106c2da0-ffff8000106c3500: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08612e8)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
```
**Symbols:**

```
c08612e8-c0861964: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083f430)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
c00000000083f430-c00000000083fb88: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a7d0c)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
```
**Symbols:**

```
ffffffe0004a7d0c-ffffffe0004a81c6: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562d30)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff81562d30-ffffffff81563311: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81553b80)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff81553b80-ffffffff81554161: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815618a0)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff815618a0-ffffffff81561e81: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int gpio_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157b790)
Location: drivers/gpio/gpiolib.c:1036
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl_compat
```
**Symbols:**

```
ffffffff8157b790-ffffffff8157bd71: gpio_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filp</code>
</li>
</ul>
</details>
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
