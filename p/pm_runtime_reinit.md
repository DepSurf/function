# Function: <code>pm_runtime_reinit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9f90)
Location: drivers/base/power/runtime.c:1424
Inline: True
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff815a9f90-ffffffff815aa015: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d89a0)
Location: drivers/base/power/runtime.c:1512
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff815d89a0-ffffffff815d8a25: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ed4a0)
Location: drivers/base/power/runtime.c:1512
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff815ed4a0-ffffffff815ed525: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654850)
Location: drivers/base/power/runtime.c:1503
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff81654850-ffffffff816548d5: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81690120)
Location: drivers/base/power/runtime.c:1503
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff81690120-ffffffff8169019f: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816b0780)
Location: drivers/base/power/runtime.c:1511
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff816b0780-ffffffff816b07ff: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ea370)
Location: drivers/base/power/runtime.c:1594
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff816ea370-ffffffff816ea3f2: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170e3d0)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff8170e3d0-ffffffff8170e452: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c9dc6)
Location: drivers/base/power/runtime.c:1621
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817c9d20-ffffffff817c9da2: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817de8b6)
Location: drivers/base/power/runtime.c:1653
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817de810-ffffffff817de892: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c2cb6)
Location: drivers/base/power/runtime.c:1654
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817c2c10-ffffffff817c2c92: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184d046)
Location: drivers/base/power/runtime.c:1690
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8184cfa0-ffffffff8184d022: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81992416)
Location: drivers/base/power/runtime.c:1730
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81992370-ffffffff819923fd: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b02876)
Location: drivers/base/power/runtime.c:1744
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81b027c0-ffffffff81b0284d: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b50926)
Location: drivers/base/power/runtime.c:1744
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81b50870-ffffffff81b508fd: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba8ea6)
Location: drivers/base/power/runtime.c:1745
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
Direct callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81ba8df0-ffffffff81ba8e7d: pm_runtime_reinit (STB_GLOBAL)
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
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fdf40)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffff8000108fdf40-ffff8000108fe024: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e8ae0)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
c09e8ae0-c09e8b70: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099b140)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
c00000000099b140-c00000000099b260: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c992)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffe00058c992-ffffffe00058ca4c: pm_runtime_reinit (STB_GLOBAL)
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
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d3b20)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff816d3b20-ffffffff816d3ba2: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816aedd0)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff816aedd0-ffffffff816aee4c: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81702090)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff81702090-ffffffff81702112: pm_runtime_reinit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_reinit(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c8c0)
Location: drivers/base/power/runtime.c:1596
Inline: True
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
```
**Symbols:**

```
ffffffff8171c8c0-ffffffff8171c939: pm_runtime_reinit (STB_GLOBAL)
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
