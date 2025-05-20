# Function: <code>uinput_inject_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81672797)
Location: drivers/input/misc/uinput.c:436
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff816d3027)
Location: drivers/input/misc/uinput.c:514
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
In drivers/input/misc/uinput.c (ffffffff81702d97)
Location: drivers/input/misc/uinput.c:522
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
In drivers/input/misc/uinput.c (ffffffff817185b4)
Location: drivers/input/misc/uinput.c:523
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
In drivers/input/misc/uinput.c (ffffffff817898ce)
Location: drivers/input/misc/uinput.c:578
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
In drivers/input/misc/uinput.c (ffffffff817cad32)
Location: drivers/input/misc/uinput.c:581
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
In drivers/input/misc/uinput.c (ffffffff817f209e)
Location: drivers/input/misc/uinput.c:582
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
In drivers/input/misc/uinput.c (ffffffff8183234d)
Location: drivers/input/misc/uinput.c:569
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
In drivers/input/misc/uinput.c (ffffffff81863c8d)
Location: drivers/input/misc/uinput.c:572
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
ssize_t uinput_inject_events(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff819375c0)
Location: drivers/input/misc/uinput.c:572
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff819375c0-ffffffff8193774a: uinput_inject_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t uinput_inject_events(struct uinput_device *udev, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff8193d9b0)
Location: drivers/input/misc/uinput.c:572
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff8193d9b0-ffffffff8193db3a: uinput_inject_events (STB_LOCAL)
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
In drivers/input/misc/uinput.c (ffffffff81920e2d)
Location: drivers/input/misc/uinput.c:572
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff819c3bfd)
Location: drivers/input/misc/uinput.c:572
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81b246b4)
Location: drivers/input/misc/uinput.c:572
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81cb7b64)
Location: drivers/input/misc/uinput.c:572
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81d1f234)
Location: drivers/input/misc/uinput.c:601
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81dd4f64)
Location: drivers/input/misc/uinput.c:601
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/misc/uinput.c (ffff800010aa4218)
Location: drivers/input/misc/uinput.c:572
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
In drivers/input/misc/uinput.c (c0b83fe0)
Location: drivers/input/misc/uinput.c:572
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
In drivers/input/misc/uinput.c (c000000000b85920)
Location: drivers/input/misc/uinput.c:572
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
In drivers/input/misc/uinput.c (ffffffe0006b2100)
Location: drivers/input/misc/uinput.c:572
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
In drivers/input/misc/uinput.c (ffffffff8181693d)
Location: drivers/input/misc/uinput.c:572
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
In drivers/input/misc/uinput.c (ffffffff817de03d)
Location: drivers/input/misc/uinput.c:572
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
In drivers/input/misc/uinput.c (ffffffff81857e1d)
Location: drivers/input/misc/uinput.c:572
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
In drivers/input/misc/uinput.c (ffffffff81872f1d)
Location: drivers/input/misc/uinput.c:572
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
</ul>
