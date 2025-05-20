# Function: <code>uinput_events_to_user</code>

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
In drivers/input/misc/uinput.c (ffffffff81672c1c)
Location: drivers/input/misc/uinput.c:502
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff816d340d)
Location: drivers/input/misc/uinput.c:580
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff81703175)
Location: drivers/input/misc/uinput.c:588
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff8171894b)
Location: drivers/input/misc/uinput.c:589
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff81789bb9)
Location: drivers/input/misc/uinput.c:644
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:647
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:649
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:636
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t uinput_events_to_user(struct uinput_device *udev, char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81937270)
Location: drivers/input/misc/uinput.c:639
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_read
```
**Symbols:**

```
ffffffff81937270-ffffffff819373f2: uinput_events_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t uinput_events_to_user(struct uinput_device *udev, char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff8193d660)
Location: drivers/input/misc/uinput.c:639
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_read
```
**Symbols:**

```
ffffffff8193d660-ffffffff8193d7e2: uinput_events_to_user (STB_LOCAL)
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff81b23c61)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff81cb6ef1)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff81d1e591)
Location: drivers/input/misc/uinput.c:673
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffff81dd4291)
Location: drivers/input/misc/uinput.c:673
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (ffffffe0006b2266)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
In drivers/input/misc/uinput.c (0)
Location: drivers/input/misc/uinput.c:639
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
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
