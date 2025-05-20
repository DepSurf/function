# Function: <code>__platform_get_irq_byname</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81701ce5)
Location: drivers/base/platform.c:245
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff817bc785)
Location: drivers/base/platform.c:303
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff817d1485)
Location: drivers/base/platform.c:455
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff817b4eb5)
Location: drivers/base/platform.c:454
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff8183e3a5)
Location: drivers/base/platform.c:434
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff819811e5)
Location: drivers/base/platform.c:438
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __platform_get_irq_byname(struct platform_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aef470)
Location: drivers/base/platform.c:438
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff81aef470-ffffffff81aef543: __platform_get_irq_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq_byname(struct platform_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3d860)
Location: drivers/base/platform.c:438
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff81b3d860-ffffffff81b3d923: __platform_get_irq_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq_byname(struct platform_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b953a0)
Location: drivers/base/platform.c:439
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff81b953a0-ffffffff81b95463: __platform_get_irq_byname (STB_LOCAL)
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
int __platform_get_irq_byname(struct platform_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ed0c8)
Location: drivers/base/platform.c:245
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffff8000108ed0c8-ffff8000108ed130: __platform_get_irq_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __platform_get_irq_byname(struct platform_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09db04c)
Location: drivers/base/platform.c:245
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
c09db04c-c09db0c0: __platform_get_irq_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq_byname(struct platform_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c0000000009863b0)
Location: drivers/base/platform.c:245
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
c0000000009863b0-c000000000986448: __platform_get_irq_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq_byname(struct platform_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580f8a)
Location: drivers/base/platform.c:245
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffe000580f8a-ffffffe000580fe4: __platform_get_irq_byname (STB_LOCAL)
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
In drivers/base/platform.c (ffffffff816c7435)
Location: drivers/base/platform.c:245
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff816a2735)
Location: drivers/base/platform.c:245
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff816f59a5)
Location: drivers/base/platform.c:245
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
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
In drivers/base/platform.c (ffffffff81710235)
Location: drivers/base/platform.c:245
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
