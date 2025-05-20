# Function: <code>__cpu_device_create</code>

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
In drivers/base/cpu.c (ffffffff8154ec8b)
Location: drivers/base/cpu.c:397
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff815a0a7b)
Location: drivers/base/cpu.c:397
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff815cf0eb)
Location: drivers/base/cpu.c:398
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff815e3b71)
Location: drivers/base/cpu.c:400
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff8164ad81)
Location: drivers/base/cpu.c:410
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff816863d7)
Location: drivers/base/cpu.c:413
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff816a6077)
Location: drivers/base/cpu.c:413
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff816df097)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff817032e7)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *__cpu_device_create(struct device *parent, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff817bd450)
Location: drivers/base/cpu.c:409
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff817bd450-ffffffff817bd50b: __cpu_device_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *__cpu_device_create(struct device *parent, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff817d21c0)
Location: drivers/base/cpu.c:407
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_device_create
```
**Symbols:**

```
ffffffff817d21c0-ffffffff817d227b: __cpu_device_create (STB_LOCAL)
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
In drivers/base/cpu.c (ffffffff817b5c57)
Location: drivers/base/cpu.c:407
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff8183f157)
Location: drivers/base/cpu.c:407
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff8198237f)
Location: drivers/base/cpu.c:407
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff81af01bf)
Location: drivers/base/cpu.c:407
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff81b3e31f)
Location: drivers/base/cpu.c:407
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff81b95f76)
Location: drivers/base/cpu.c:436
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffff8000108eeae4)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (c09dc4f0)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (c000000000987e30)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffe000581944)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff816c8a37)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff816a3d67)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff816f6fa7)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
In drivers/base/cpu.c (ffffffff81711847)
Location: drivers/base/cpu.c:414
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
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
