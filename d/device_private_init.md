# Function: <code>device_private_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_private_init(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548380)
Location: drivers/base/core.c:991
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81548380-ffffffff815483ef: device_private_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_private_init(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81599fd0)
Location: drivers/base/core.c:991
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81599fd0-ffffffff8159a03e: device_private_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_private_init(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8560)
Location: drivers/base/core.c:1573
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815c8560-ffffffff815c85ce: device_private_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_private_init(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dd230)
Location: drivers/base/core.c:1571
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815dd230-ffffffff815dd29e: device_private_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_private_init(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644230)
Location: drivers/base/core.c:1706
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81644230-ffffffff8164429e: device_private_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_private_init(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167f680)
Location: drivers/base/core.c:1748
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8167f680-ffffffff8167f6ee: device_private_init (STB_GLOBAL)
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
In drivers/base/core.c (ffffffff8169e624)
Location: drivers/base/core.c:1824
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff816d6e18)
Location: drivers/base/core.c:2023
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff816faf18)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff817b413e)
Location: drivers/base/core.c:2540
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff817ca794)
Location: drivers/base/core.c:2949
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff817ae099)
Location: drivers/base/core.c:3167
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff81837060)
Location: drivers/base/core.c:3235
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff819790af)
Location: drivers/base/core.c:3270
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff81ae5c4d)
Location: drivers/base/core.c:3468
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff81b34031)
Location: drivers/base/core.c:3469
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff81b8b9d1)
Location: drivers/base/core.c:3482
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffff8000108e5500)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (c09d3cb4)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (c00000000097aed0)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffe00057a20c)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff816c0708)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff8169b9b8)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff816eebd8)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff817090f8)
Location: drivers/base/core.c:2060
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
</ul>
