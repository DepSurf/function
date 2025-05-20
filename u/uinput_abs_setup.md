# Function: <code>uinput_abs_setup</code>

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
In drivers/input/misc/uinput.c (ffffffff816d2834)
Location: drivers/input/misc/uinput.c:416
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff81702454)
Location: drivers/input/misc/uinput.c:424
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff81717d23)
Location: drivers/input/misc/uinput.c:425
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff81788ecc)
Location: drivers/input/misc/uinput.c:480
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff817ca105)
Location: drivers/input/misc/uinput.c:483
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff817f17c5)
Location: drivers/input/misc/uinput.c:484
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff81832f11)
Location: drivers/input/misc/uinput.c:471
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff8186484b)
Location: drivers/input/misc/uinput.c:474
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff8193817d)
Location: drivers/input/misc/uinput.c:474
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff8193e56d)
Location: drivers/input/misc/uinput.c:474
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int uinput_abs_setup(struct uinput_device *udev, struct uinput_setup *arg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:474
Inline: False
```
**Symbols:**

```
ffffffff81921060-ffffffff819211ad: uinput_abs_setup (STB_LOCAL)
ffffffff81c16557-ffffffff81c1659a: uinput_abs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uinput_abs_setup(struct uinput_device *udev, struct uinput_setup *arg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:474
Inline: False
```
**Symbols:**

```
ffffffff819c3e30-ffffffff819c3f7d: uinput_abs_setup (STB_LOCAL)
ffffffff81d24f99-ffffffff81d24fdc: uinput_abs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uinput_abs_setup(struct uinput_device *udev, struct uinput_setup *arg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:474
Inline: False
```
**Symbols:**

```
ffffffff81b24a80-ffffffff81b24be6: uinput_abs_setup (STB_LOCAL)
ffffffff81ef0d85-ffffffff81ef0dbd: uinput_abs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uinput_abs_setup(struct uinput_device *udev, struct uinput_setup *arg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81cb7f70)
Location: drivers/input/misc/uinput.c:474
Inline: False
```
**Symbols:**

```
ffffffff81cb7f70-ffffffff81cb8101: uinput_abs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uinput_abs_setup(struct uinput_device *udev, struct uinput_setup *arg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81d1f6f0)
Location: drivers/input/misc/uinput.c:475
Inline: False
```
**Symbols:**

```
ffffffff81d1f6f0-ffffffff81d1f881: uinput_abs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uinput_abs_setup(struct uinput_device *udev, struct uinput_setup *arg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81dd5420)
Location: drivers/input/misc/uinput.c:475
Inline: False
```
**Symbols:**

```
ffffffff81dd5420-ffffffff81dd55b1: uinput_abs_setup (STB_LOCAL)
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
In drivers/input/misc/uinput.c (ffff800010aa5eb0)
Location: drivers/input/misc/uinput.c:474
Inline: True
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
In drivers/input/misc/uinput.c (c0b84a8c)
Location: drivers/input/misc/uinput.c:474
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
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
In drivers/input/misc/uinput.c (c000000000b864e0)
Location: drivers/input/misc/uinput.c:474
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
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
In drivers/input/misc/uinput.c (ffffffe0006b189a)
Location: drivers/input/misc/uinput.c:474
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
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
In drivers/input/misc/uinput.c (ffffffff818174fb)
Location: drivers/input/misc/uinput.c:474
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff817debeb)
Location: drivers/input/misc/uinput.c:474
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff818589db)
Location: drivers/input/misc/uinput.c:474
Inline: True
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
In drivers/input/misc/uinput.c (ffffffff81873abb)
Location: drivers/input/misc/uinput.c:474
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
