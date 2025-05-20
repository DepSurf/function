# Function: <code>of_find_backlight</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81551810)
Location: drivers/video/backlight/backlight.c:598
Inline: True
```
**Symbols:**

```
ffffffff81551810-ffffffff8155181d: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815690a0)
Location: drivers/video/backlight/backlight.c:598
Inline: True
```
**Symbols:**

```
ffffffff815690a0-ffffffff815690ad: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81599910)
Location: drivers/video/backlight/backlight.c:599
Inline: True
```
**Symbols:**

```
ffffffff81599910-ffffffff8159991d: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815bacb0)
Location: drivers/video/backlight/backlight.c:618
Inline: True
```
**Symbols:**

```
ffffffff815bacb0-ffffffff815bacbd: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff81664b50)
Location: drivers/video/backlight/backlight.c:639
Inline: True
```
**Symbols:**

```
ffffffff81664b50-ffffffff81664b5d: of_find_backlight (STB_GLOBAL)
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
In drivers/video/backlight/backlight.c (0)
Location: drivers/video/backlight/backlight.c:676
Inline: True
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
In drivers/video/backlight/backlight.c (0)
Location: drivers/video/backlight/backlight.c:676
Inline: True
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
In drivers/video/backlight/backlight.c (0)
Location: drivers/video/backlight/backlight.c:676
Inline: True
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
In drivers/video/backlight/backlight.c (0)
Location: drivers/video/backlight/backlight.c:688
Inline: True
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
In drivers/video/backlight/backlight.c (0)
Location: drivers/video/backlight/backlight.c:688
Inline: True
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
In drivers/video/backlight/backlight.c (0)
Location: drivers/video/backlight/backlight.c:688
Inline: True
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
In drivers/video/backlight/backlight.c (0)
Location: drivers/video/backlight/backlight.c:688
Inline: True
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
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffff800010741be8)
Location: drivers/video/backlight/backlight.c:618
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
```
**Symbols:**

```
ffff800010741be8-ffff800010741ca0: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (c08c663c)
Location: drivers/video/backlight/backlight.c:618
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
```
**Symbols:**

```
c08c663c-c08c66f4: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (c0000000008a1df0)
Location: drivers/video/backlight/backlight.c:618
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
```
**Symbols:**

```
c0000000008a1df0-c0000000008a1f30: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815aee00)
Location: drivers/video/backlight/backlight.c:618
Inline: True
```
**Symbols:**

```
ffffffff815aee00-ffffffff815aee0d: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff8159df90)
Location: drivers/video/backlight/backlight.c:618
Inline: True
```
**Symbols:**

```
ffffffff8159df90-ffffffff8159df9d: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815af390)
Location: drivers/video/backlight/backlight.c:618
Inline: True
```
**Symbols:**

```
ffffffff815af390-ffffffff815af39d: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffffffff815c8e00)
Location: drivers/video/backlight/backlight.c:618
Inline: True
```
**Symbols:**

```
ffffffff815c8e00-ffffffff815c8e0d: of_find_backlight (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
