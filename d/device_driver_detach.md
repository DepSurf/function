# Function: <code>device_driver_detach</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dc220)
Location: drivers/base/dd.c:1192
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff816dc220-ffffffff816dc236: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81700260)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff81700260-ffffffff81700276: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817ba0c0)
Location: drivers/base/dd.c:1183
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff817ba0c0-ffffffff817ba160: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cef10)
Location: drivers/base/dd.c:1231
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff817cef10-ffffffff817cefb0: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b2920)
Location: drivers/base/dd.c:1246
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff817b2920-ffffffff817b29c0: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1275
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff81d030c7-ffffffff81d030f1: device_driver_detach.cold (STB_LOCAL)
ffffffff8183bd70-ffffffff8183be37: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8197e650)
Location: drivers/base/dd.c:1285
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff8197e650-ffffffff8197e670: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81aebbe0)
Location: drivers/base/dd.c:1313
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff81aebbe0-ffffffff81aebc00: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b39e20)
Location: drivers/base/dd.c:1329
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff81b39e20-ffffffff81b39e40: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b918e0)
Location: drivers/base/dd.c:1329
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff81b918e0-ffffffff81b91900: device_driver_detach (STB_GLOBAL)
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
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eb588)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffff8000108eb588-ffff8000108eb5bc: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d966c)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
c09d966c-c09d9690: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000982c00)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
c000000000982c00-c000000000982c1c: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057f18e)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffe00057f18e-ffffffe00057f1bc: device_driver_detach (STB_GLOBAL)
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
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c5a50)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff816c5a50-ffffffff816c5a66: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a0cd0)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff816a0cd0-ffffffff816a0ce6: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f3f20)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff816f3f20-ffffffff816f3f36: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_driver_detach(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170e750)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
```
**Symbols:**

```
ffffffff8170e750-ffffffff8170e766: device_driver_detach (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
