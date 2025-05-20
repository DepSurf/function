# Function: <code>device_add_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548647)
Location: drivers/base/core.c:469
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
```
```
In drivers/base/bus.c (ffffffff8154aa66)
Location: drivers/base/bus.c:470
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a355)
Location: drivers/base/core.c:469
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
```
```
In drivers/base/bus.c (ffffffff8159c68e)
Location: drivers/base/bus.c:469
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8841)
Location: drivers/base/core.c:1035
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
```
```
In drivers/base/bus.c (ffffffff815cabee)
Location: drivers/base/bus.c:469
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_add_device
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
In drivers/base/core.c (ffffffff815dd5ab)
Location: drivers/base/core.c:1033
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff816445ae)
Location: drivers/base/core.c:1168
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff8167f994)
Location: drivers/base/core.c:1210
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffff8169e71c)
Location: drivers/base/core.c:1284
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
In drivers/base/core.c (ffffffff816d6c56)
Location: drivers/base/core.c:1429
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
In drivers/base/core.c (ffffffff816fad56)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (ffffffff817b3f64)
Location: drivers/base/core.c:1944
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_add_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c6ab0)
Location: drivers/base/core.c:2345
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817c6ab0-ffffffff817c6c14: device_add_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_add_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817a9f70)
Location: drivers/base/core.c:2557
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817a9f70-ffffffff817aa0d9: device_add_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_add_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818330f0)
Location: drivers/base/core.c:2613
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff818330f0-ffffffff818332af: device_add_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_add_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81976850)
Location: drivers/base/core.c:2624
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81976850-ffffffff81976a78: device_add_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_add_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae32f0)
Location: drivers/base/core.c:2822
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81ae32f0-ffffffff81ae3518: device_add_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_add_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b31320)
Location: drivers/base/core.c:2828
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b31320-ffffffff81b31548: device_add_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_add_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88b50)
Location: drivers/base/core.c:2843
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b88b50-ffffffff81b88d78: device_add_attrs (STB_LOCAL)
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
In drivers/base/core.c (ffff8000108e5384)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (c09d3b24)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (c00000000097accc)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (ffffffe00057a0c8)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (ffffffff816c0546)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (ffffffff8169b7f6)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (ffffffff816eea16)
Location: drivers/base/core.c:1466
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
In drivers/base/core.c (ffffffff81708f36)
Location: drivers/base/core.c:1466
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
