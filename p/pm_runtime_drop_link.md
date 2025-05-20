# Function: <code>pm_runtime_drop_link</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8c00)
Location: drivers/base/power/runtime.c:1617
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff815d8c00-ffffffff815d8c66: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ed700)
Location: drivers/base/power/runtime.c:1617
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff815ed700-ffffffff815ed74f: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654ab0)
Location: drivers/base/power/runtime.c:1608
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81654ab0-ffffffff81654aff: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81690370)
Location: drivers/base/power/runtime.c:1608
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81690370-ffffffff816903c5: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816b09d0)
Location: drivers/base/power/runtime.c:1616
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff816b09d0-ffffffff816b0a25: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1703
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff816ea6b0-ffffffff816ea6c9: pm_runtime_drop_link.cold (STB_LOCAL)
ffffffff816ea600-ffffffff816ea64b: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170e660)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff8170e660-ffffffff8170e6ab: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817ca040)
Location: drivers/base/power/runtime.c:1733
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff817ca040-ffffffff817ca08b: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817deb10)
Location: drivers/base/power/runtime.c:1751
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff817deb10-ffffffff817deb91: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c2f10)
Location: drivers/base/power/runtime.c:1752
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff817c2f10-ffffffff817c2f91: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184d2a0)
Location: drivers/base/power/runtime.c:1788
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff8184d2a0-ffffffff8184d30a: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff819925f0)
Location: drivers/base/power/runtime.c:1820
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff819925f0-ffffffff81992692: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b02a90)
Location: drivers/base/power/runtime.c:1834
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81b02a90-ffffffff81b02b32: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b50b40)
Location: drivers/base/power/runtime.c:1834
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81b50b40-ffffffff81b50be2: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba90c0)
Location: drivers/base/power/runtime.c:1835
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81ba90c0-ffffffff81ba9162: pm_runtime_drop_link (STB_GLOBAL)
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
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fe300)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffff8000108fe300-ffff8000108fe3b4: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e8dc4)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
c09e8dc4-c09e8e34: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099b670)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
c00000000099b670-c00000000099b744: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058ccbc)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffe00058ccbc-ffffffe00058cd3c: pm_runtime_drop_link (STB_GLOBAL)
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
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d3db0)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff816d3db0-ffffffff816d3dfb: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816af050)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff816af050-ffffffff816af095: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81702320)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff81702320-ffffffff8170236b: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_runtime_drop_link(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171cb40)
Location: drivers/base/power/runtime.c:1708
Inline: False
Direct callers:
  - drivers/base/core.c:__device_link_del
```
**Symbols:**

```
ffffffff8171cb40-ffffffff8171cb82: pm_runtime_drop_link (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device_link *link</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
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
