# Function: <code>__device_release_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __device_release_driver(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8154b5f0)
Location: drivers/base/dd.c:669
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:driver_detach
```
**Symbols:**

```
ffffffff8154b5f0-ffffffff8154b732: __device_release_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __device_release_driver(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d2e0)
Location: drivers/base/dd.c:759
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff8159d2e0-ffffffff8159d432: __device_release_driver (STB_LOCAL)
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
In drivers/base/dd.c (ffffffff815cc2f8)
Location: drivers/base/dd.c:783
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff815e0ed5)
Location: drivers/base/dd.c:790
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff81647fe5)
Location: drivers/base/dd.c:827
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff816834f2)
Location: drivers/base/dd.c:841
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff816a31f2)
Location: drivers/base/dd.c:928
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff816dc1d3)
Location: drivers/base/dd.c:1084
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff8170020f)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __device_release_driver(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b8e90)
Location: drivers/base/dd.c:1073
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff817b8e90-ffffffff817b90bd: __device_release_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __device_release_driver(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cdc00)
Location: drivers/base/dd.c:1119
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff817cdc00-ffffffff817cde42: __device_release_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __device_release_driver(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b1610)
Location: drivers/base/dd.c:1141
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff817b1610-ffffffff817b184b: __device_release_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __device_release_driver(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff8183a870-ffffffff8183aaf9: __device_release_driver (STB_LOCAL)
ffffffff81d02de8-ffffffff81d02e12: __device_release_driver.cold (STB_LOCAL)
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
In drivers/base/dd.c (ffffffff8197e471)
Location: drivers/base/dd.c:1191
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff81aeb9e1)
Location: drivers/base/dd.c:1219
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff81b39c51)
Location: drivers/base/dd.c:1241
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff81b91711)
Location: drivers/base/dd.c:1241
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffff8000108eb520)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (c09d9628)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (c000000000982ba0)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffe00057f04e)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff816c59ff)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff816a0c7f)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff816f3ecf)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
In drivers/base/dd.c (ffffffff8170e6ff)
Location: drivers/base/dd.c:1099
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
