# Function: <code>device_links_driver_cleanup</code>

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
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7a70)
Location: drivers/base/core.c:471
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff815c7a70-ffffffff815c7b0d: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc720)
Location: drivers/base/core.c:472
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff815dc720-ffffffff815dc79a: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81643760)
Location: drivers/base/core.c:475
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81643760-ffffffff816437da: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167eb10)
Location: drivers/base/core.c:508
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff8167eb10-ffffffff8167eb86: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ef30)
Location: drivers/base/core.c:540
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff8169ef30-ffffffff8169efc7: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:685
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816d9155-ffffffff816d9185: device_links_driver_cleanup.cold (STB_LOCAL)
ffffffff816d7560-ffffffff816d7606: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb670)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816fb670-ffffffff816fb72d: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b4c50)
Location: drivers/base/core.c:1031
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
```
**Symbols:**

```
ffffffff817b4c50-ffffffff817b4d1d: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c94a0)
Location: drivers/base/core.c:1305
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
```
**Symbols:**

```
ffffffff817c94a0-ffffffff817c957d: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817acc10)
Location: drivers/base/core.c:1387
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
```
**Symbols:**

```
ffffffff817acc10-ffffffff817acced: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81835f00)
Location: drivers/base/core.c:1402
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_release_driver
```
**Symbols:**

```
ffffffff81835f00-ffffffff81835fdd: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81977e80)
Location: drivers/base/core.c:1414
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81977e80-ffffffff81977f72: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae4670)
Location: drivers/base/core.c:1542
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81ae4670-ffffffff81ae4762: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b32960)
Location: drivers/base/core.c:1481
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81b32960-ffffffff81b32a52: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8a270)
Location: drivers/base/core.c:1484
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81b8a270-ffffffff81b8a362: device_links_driver_cleanup (STB_GLOBAL)
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
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e5e98)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffff8000108e5e98-ffff8000108e5f68: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d4524)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
c09d4524-c09d4614: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097b990)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
c00000000097b990-c00000000097baa4: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a9ae)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffe00057a9ae-ffffffe00057aa88: device_links_driver_cleanup (STB_GLOBAL)
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
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0e60)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816c0e60-ffffffff816c0f1d: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c110)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff8169c110-ffffffff8169c1cd: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef330)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff816ef330-ffffffff816ef3ed: device_links_driver_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_links_driver_cleanup(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709b70)
Location: drivers/base/core.c:722
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
```
**Symbols:**

```
ffffffff81709b70-ffffffff81709c2d: device_links_driver_cleanup (STB_GLOBAL)
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
