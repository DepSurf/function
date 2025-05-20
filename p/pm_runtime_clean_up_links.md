# Function: <code>pm_runtime_clean_up_links</code>

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
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8a50)
Location: drivers/base/power/runtime.c:1554
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff815d8a50-ffffffff815d8ae0: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ed550)
Location: drivers/base/power/runtime.c:1554
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff815ed550-ffffffff815ed5dd: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654900)
Location: drivers/base/power/runtime.c:1545
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81654900-ffffffff8165498d: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816901c0)
Location: drivers/base/power/runtime.c:1545
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816901c0-ffffffff8169024c: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816b0820)
Location: drivers/base/power/runtime.c:1553
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816b0820-ffffffff816b08ac: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ea430)
Location: drivers/base/power/runtime.c:1636
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816ea430-ffffffff816ea4bb: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170e490)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff8170e490-ffffffff8170e51b: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c9e40)
Location: drivers/base/power/runtime.c:1663
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
```
**Symbols:**

```
ffffffff817c9e40-ffffffff817c9ecb: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fe060)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffff8000108fe060-ffff8000108fe130: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e8b9c)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
c09e8b9c-c09e8c60: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099b2b0)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
c00000000099b2b0-c00000000099b3d0: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058ca82)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffe00058ca82-ffffffe00058cb30: pm_runtime_clean_up_links (STB_GLOBAL)
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
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d3be0)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816d3be0-ffffffff816d3c6b: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816aee80)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816aee80-ffffffff816aef0b: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81702150)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81702150-ffffffff817021db: pm_runtime_clean_up_links (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_runtime_clean_up_links(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c970)
Location: drivers/base/power/runtime.c:1638
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff8171c970-ffffffff8171c9fb: pm_runtime_clean_up_links (STB_GLOBAL)
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
