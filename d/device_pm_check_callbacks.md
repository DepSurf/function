# Function: <code>device_pm_check_callbacks</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ad850)
Location: drivers/base/power/main.c:1756
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff815ad850-ffffffff815ad91c: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815dc610)
Location: drivers/base/power/main.c:1831
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff815dc610-ffffffff815dc6dc: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815f1180)
Location: drivers/base/power/main.c:1834
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff815f1180-ffffffff815f124a: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81658700)
Location: drivers/base/power/main.c:1927
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff81658700-ffffffff81658811: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816940b0)
Location: drivers/base/power/main.c:2103
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff816940b0-ffffffff816941c1: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b4730)
Location: drivers/base/power/main.c:2109
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff816b4730-ffffffff816b4841: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ee600)
Location: drivers/base/power/main.c:2097
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff816ee600-ffffffff816ee701: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817125e0)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff817125e0-ffffffff817126e1: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cde10)
Location: drivers/base/power/main.c:1995
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff817cde10-ffffffff817cdf0a: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e2720)
Location: drivers/base/power/main.c:1994
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff817e2720-ffffffff817e281a: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c6b00)
Location: drivers/base/power/main.c:1995
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff817c6b00-ffffffff817c6bfa: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81850ee0)
Location: drivers/base/power/main.c:2023
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff81850ee0-ffffffff81850fda: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff819969c0)
Location: drivers/base/power/main.c:2019
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff819969c0-ffffffff81996acd: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b07730)
Location: drivers/base/power/main.c:2019
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff81b07730-ffffffff81b0783d: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b55780)
Location: drivers/base/power/main.c:2019
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff81b55780-ffffffff81b5588d: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81badd40)
Location: drivers/base/power/main.c:2018
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff81badd40-ffffffff81bade4d: device_pm_check_callbacks (STB_GLOBAL)
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
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010903178)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffff800010903178-ffff8000109032c8: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09ed578)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
c09ed578-c09ed688: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c0000000009a18b0)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
c0000000009a18b0-c0000000009a1a54: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/power/power.h:140
Inline: True
```
```
In drivers/base/power/common.c (0)
Location: drivers/base/power/power.h:140
Inline: True
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
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d8960)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff816d8960-ffffffff816d8a61: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b2fb0)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff816b2fb0-ffffffff816b30ab: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817062a0)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff817062a0-ffffffff817063a1: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_pm_check_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81720cc0)
Location: drivers/base/power/main.c:2118
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/common.c:dev_pm_domain_set
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_add
```
**Symbols:**

```
ffffffff81720cc0-ffffffff81720db4: device_pm_check_callbacks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
