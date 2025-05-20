# Function: <code>device_platform_notify</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d160)
Location: drivers/base/core.c:733
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8169d160-ffffffff8169d1d0: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d5fb0)
Location: drivers/base/core.c:878
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816d5fb0-ffffffff816d601f: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9ff0)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816f9ff0-ffffffff816fa05f: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2f40)
Location: drivers/base/core.c:1393
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817b2f40-ffffffff817b2fb0: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c79a0)
Location: drivers/base/core.c:1794
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817c79a0-ffffffff817c7a10: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aae10)
Location: drivers/base/core.c:2006
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817aae10-ffffffff817aae80: device_platform_notify (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81836f19)
Location: drivers/base/core.c:2042
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
In drivers/base/core.c (ffffffff81978f27)
Location: drivers/base/core.c:2054
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
In drivers/base/core.c (ffffffff81ae5a3b)
Location: drivers/base/core.c:2291
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
In drivers/base/core.c (ffffffff81b33e0b)
Location: drivers/base/core.c:2297
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
In drivers/base/core.c (ffffffff81b8b797)
Location: drivers/base/core.c:2312
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e47b0)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffff8000108e47b0-ffff8000108e4868: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d31f0)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c09d31f0-c09d327c: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000979bb0)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c000000000979bb0-c000000000979c78: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579684)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffe000579684-ffffffe000579700: device_platform_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf7e0)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816bf7e0-ffffffff816bf84f: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169aa90)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8169aa90-ffffffff8169aaff: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816edcb0)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816edcb0-ffffffff816edd1f: device_platform_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int device_platform_notify(struct device *dev, enum kobject_action action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817084f0)
Location: drivers/base/core.c:915
Inline: True
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817084f0-ffffffff8170855f: device_platform_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
