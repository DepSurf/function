# Function: <code>usbdev_do_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161c960)
Location: drivers/usb/core/devio.c:2138
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff8161c960-ffffffff8161d8f1: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167d030)
Location: drivers/usb/core/devio.c:2364
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff8167d030-ffffffff8167e14a: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816aadb0)
Location: drivers/usb/core/devio.c:2364
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff816aadb0-ffffffff816abece: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bfdb0)
Location: drivers/usb/core/devio.c:2344
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff816bfdb0-ffffffff816c0f1a: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8172b7e0)
Location: drivers/usb/core/devio.c:2354
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff8172b7e0-ffffffff8172c94a: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8176a8d0)
Location: drivers/usb/core/devio.c:2365
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff8176a8d0-ffffffff8176b9b2: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178ee60)
Location: drivers/usb/core/devio.c:2365
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff8178ee60-ffffffff8178ff42: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2390
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff817ccf00-ffffffff817cde19: usbdev_do_ioctl (STB_LOCAL)
ffffffff817ce41c-ffffffff817ce865: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff817fdb90-ffffffff817feb98: usbdev_do_ioctl (STB_LOCAL)
ffffffff817ff210-ffffffff817ff635: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff818ce220-ffffffff818cf076: usbdev_do_ioctl (STB_LOCAL)
ffffffff818cf795-ffffffff818cfb92: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2489
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff818d9190-ffffffff818da006: usbdev_do_ioctl (STB_LOCAL)
ffffffff81c1e612-ffffffff81c1e9d5: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff818bc310-ffffffff818bd468: usbdev_do_ioctl (STB_LOCAL)
ffffffff81c10417-ffffffff81c10866: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2572
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff819522d0-ffffffff819537ab: usbdev_do_ioctl (STB_LOCAL)
ffffffff81d17432-ffffffff81d17b83: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2588
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff81aab970-ffffffff81aacfdd: usbdev_do_ioctl (STB_LOCAL)
ffffffff81ee22e7-ffffffff81ee2a1e: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2588
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff81c32e50-ffffffff81c3480e: usbdev_do_ioctl (STB_LOCAL)
ffffffff8209eb00-ffffffff8209edc6: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2597
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff81c9a120-ffffffff81c9bb2a: usbdev_do_ioctl (STB_LOCAL)
ffffffff8212008d-ffffffff82120376: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2597
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff81d4ecf0-ffffffff81d506e0: usbdev_do_ioctl (STB_LOCAL)
ffffffff82201864-ffffffff82201b4d: usbdev_do_ioctl.cold (STB_LOCAL)
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
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a314a8)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffff800010a314a8-ffff800010a32aac: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b051a0)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
c0b051a0-c0b06aa0: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000aee710)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
c000000000aee710-c000000000af02d4: usbdev_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064fd9e)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffe00064fd9e-ffffffe000650efe: usbdev_do_ioctl (STB_LOCAL)
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
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff817b5f70-ffffffff817b6f78: usbdev_do_ioctl (STB_LOCAL)
ffffffff817b75f0-ffffffff817b7a15: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff817a7990-ffffffff817a8998: usbdev_do_ioctl (STB_LOCAL)
ffffffff817a9010-ffffffff817a9435: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff817f2a10-ffffffff817f3a18: usbdev_do_ioctl (STB_LOCAL)
ffffffff817f4090-ffffffff817f44b5: usbdev_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int usbdev_do_ioctl(struct file *file, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:2477
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_ioctl
```
**Symbols:**

```
ffffffff8180cc90-ffffffff8180dc93: usbdev_do_ioctl (STB_LOCAL)
ffffffff8180e2cc-ffffffff8180e6f1: usbdev_do_ioctl.cold (STB_LOCAL)
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
