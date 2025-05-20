# Function: <code>driver_allows_async_probing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8154b5d0)
Location: drivers/base/dd.c:438
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach_driver
Direct callers:
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8154b5d0-ffffffff8154b5ef: driver_allows_async_probing.part.4 (STB_LOCAL)
ffffffff8154c0c0-ffffffff8154c0e5: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d2fc)
Location: drivers/base/dd.c:508
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach_driver
Direct callers:
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8159d2c0-ffffffff8159d2df: driver_allows_async_probing.part.3 (STB_LOCAL)
ffffffff8159deb0-ffffffff8159ded6: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff815cc32d)
Location: drivers/base/dd.c:532
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
Direct callers:
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff815cb7c0-ffffffff815cb7df: driver_allows_async_probing.part.5 (STB_LOCAL)
ffffffff815cc270-ffffffff815cc296: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff815e0ee1)
Location: drivers/base/dd.c:539
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
Direct callers:
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff815e0390-ffffffff815e03ad: driver_allows_async_probing.part.5 (STB_LOCAL)
ffffffff815e0e20-ffffffff815e0e46: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff81647ff1)
Location: drivers/base/dd.c:576
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
Direct callers:
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81647450-ffffffff8164746d: driver_allows_async_probing.part.7 (STB_LOCAL)
ffffffff81647f30-ffffffff81647f56: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff816834fe)
Location: drivers/base/dd.c:590
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
Direct callers:
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81682940-ffffffff8168295d: driver_allows_async_probing.part.12 (STB_LOCAL)
ffffffff81683410-ffffffff81683435: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff816a33e5)
Location: drivers/base/dd.c:677
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach_driver
Direct callers:
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816a2580-ffffffff816a259d: driver_allows_async_probing.part.13 (STB_LOCAL)
ffffffff816a3110-ffffffff816a3135: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dbd40)
Location: drivers/base/dd.c:736
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816dbd40-ffffffff816dbd88: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816ffd70)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816ffd70-ffffffff816ffdb8: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b9ce0)
Location: drivers/base/dd.c:723
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff817b9ce0-ffffffff817b9d2b: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817ceb30)
Location: drivers/base/dd.c:769
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff817ceb30-ffffffff817ceb7b: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b2540)
Location: drivers/base/dd.c:789
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff817b2540-ffffffff817b258b: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8183b993)
Location: drivers/base/dd.c:816
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81d03023-ffffffff81d0303e: driver_allows_async_probing.cold (STB_LOCAL)
ffffffff8183b950-ffffffff8183b9b0: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:832
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81ecb6f1-ffffffff81ecb728: driver_allows_async_probing.cold (STB_LOCAL)
ffffffff8197df80-ffffffff8197e02d: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:846
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81aea050-ffffffff81aea0fd: driver_allows_async_probing (STB_LOCAL)
ffffffff8209841a-ffffffff82098451: driver_allows_async_probing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:868
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81b383d0-ffffffff81b38481: driver_allows_async_probing (STB_LOCAL)
ffffffff8211944c-ffffffff82119483: driver_allows_async_probing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:868
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81b8fe70-ffffffff81b8ff21: driver_allows_async_probing (STB_LOCAL)
ffffffff821f740f-ffffffff821f7446: driver_allows_async_probing.cold (STB_LOCAL)
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
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eaff0)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffff8000108eaff0-ffff8000108eb058: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d911c)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
c09d911c-c09d9180: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000982480)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
c000000000982480-c000000000982524: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057ecee)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffe00057ecee-ffffffe00057ed3c: driver_allows_async_probing (STB_GLOBAL)
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
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c5560)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816c5560-ffffffff816c55a8: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a07e0)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816a07e0-ffffffff816a0828: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f3a30)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816f3a30-ffffffff816f3a78: driver_allows_async_probing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool driver_allows_async_probing(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170e260)
Location: drivers/base/dd.c:751
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8170e260-ffffffff8170e2a8: driver_allows_async_probing (STB_GLOBAL)
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
