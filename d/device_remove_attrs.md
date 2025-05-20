# Function: <code>device_remove_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81546510)
Location: drivers/base/core.c:511
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
```
In drivers/base/bus.c (ffffffff8154a600)
Location: drivers/base/bus.c:489
Inline: True
Direct callers:
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_remove_device
```
**Symbols:**

```
ffffffff81546510-ffffffff81546588: device_remove_attrs (STB_LOCAL)
ffffffff8154a600-ffffffff8154a648: device_remove_attrs.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81598180)
Location: drivers/base/core.c:511
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
```
In drivers/base/bus.c (ffffffff8159c230)
Location: drivers/base/bus.c:488
Inline: True
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
```
**Symbols:**

```
ffffffff81598180-ffffffff815981f8: device_remove_attrs (STB_LOCAL)
ffffffff8159c230-ffffffff8159c278: device_remove_attrs.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff815c5d50)
Location: drivers/base/core.c:1077
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
```
In drivers/base/bus.c (ffffffff815ca790)
Location: drivers/base/bus.c:488
Inline: True
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
```
**Symbols:**

```
ffffffff815c5d50-ffffffff815c5dc8: device_remove_attrs (STB_LOCAL)
ffffffff815ca790-ffffffff815ca7d8: device_remove_attrs.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dab70)
Location: drivers/base/core.c:1075
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815dab70-ffffffff815dabe2: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81641b20)
Location: drivers/base/core.c:1210
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81641b20-ffffffff81641b92: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167cdc0)
Location: drivers/base/core.c:1252
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8167cdc0-ffffffff8167ce32: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c750)
Location: drivers/base/core.c:1326
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8169c750-ffffffff8169c7c2: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d5560)
Location: drivers/base/core.c:1471
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816d5560-ffffffff816d55c8: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9310)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816f9310-ffffffff816f9378: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b21e0)
Location: drivers/base/core.c:1986
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817b21e0-ffffffff817b2248: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c6c20)
Location: drivers/base/core.c:2395
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817c6c20-ffffffff817c6c99: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa0e0)
Location: drivers/base/core.c:2607
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817aa0e0-ffffffff817aa159: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818332b0)
Location: drivers/base/core.c:2671
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff818332b0-ffffffff8183333a: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975cb0)
Location: drivers/base/core.c:2691
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81975cb0-ffffffff81975da3: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae1c80)
Location: drivers/base/core.c:2889
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81ae1c80-ffffffff81ae1d73: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2faa0)
Location: drivers/base/core.c:2895
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b2faa0-ffffffff81b2fb93: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b872a0)
Location: drivers/base/core.c:2910
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b872a0-ffffffff81b87393: device_remove_attrs (STB_LOCAL)
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
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e3508)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffff8000108e3508-ffff8000108e3584: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d1f80)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c09d1f80-c09d1ff0: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000978510)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c000000000978510-c0000000009785bc: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005788a8)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffe0005788a8-ffffffe000578920: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816beb00)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816beb00-ffffffff816beb68: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81699db0)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81699db0-ffffffff81699e18: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ecfd0)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816ecfd0-ffffffff816ed038: device_remove_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_remove_attrs(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81707810)
Location: drivers/base/core.c:1508
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81707810-ffffffff81707878: device_remove_attrs (STB_LOCAL)
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
