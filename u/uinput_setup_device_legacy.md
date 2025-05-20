# Function: <code>uinput_setup_device_legacy</code>

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
In drivers/input/misc/uinput.c (ffffffff816d2fb4)
Location: drivers/input/misc/uinput.c:451
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff81702d23)
Location: drivers/input/misc/uinput.c:459
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff81718521)
Location: drivers/input/misc/uinput.c:460
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff8178972d)
Location: drivers/input/misc/uinput.c:515
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff817cab13)
Location: drivers/input/misc/uinput.c:518
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff817f1e8c)
Location: drivers/input/misc/uinput.c:519
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff81832142)
Location: drivers/input/misc/uinput.c:506
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff81863a82)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81936e60)
Location: drivers/input/misc/uinput.c:509
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81936e60-ffffffff81937092: uinput_setup_device_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff8193d250)
Location: drivers/input/misc/uinput.c:509
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff8193d250-ffffffff8193d482: uinput_setup_device_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81920b50)
Location: drivers/input/misc/uinput.c:509
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81920b50-ffffffff81920d8c: uinput_setup_device_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff819c38b0)
Location: drivers/input/misc/uinput.c:509
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff819c38b0-ffffffff819c3b58: uinput_setup_device_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81b24360)
Location: drivers/input/misc/uinput.c:509
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81b24360-ffffffff81b24610: uinput_setup_device_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81cb7800)
Location: drivers/input/misc/uinput.c:509
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81cb7800-ffffffff81cb7aaf: uinput_setup_device_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81d1eea0)
Location: drivers/input/misc/uinput.c:510
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81d1eea0-ffffffff81d1f17a: uinput_setup_device_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uinput_setup_device_legacy(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81dd4bd0)
Location: drivers/input/misc/uinput.c:510
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81dd4bd0-ffffffff81dd4eaa: uinput_setup_device_legacy (STB_LOCAL)
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
In drivers/input/misc/uinput.c (ffff800010aa4060)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (c0b83e1c)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (c000000000b856d0)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffe0006b1f5c)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff81816732)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff817dde32)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff81857c12)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffffffff81872d12)
Location: drivers/input/misc/uinput.c:509
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
