# Function: <code>platform_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154e350)
Location: drivers/base/platform.c:923
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff8154e350-ffffffff8154e3e5: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815a0150)
Location: drivers/base/platform.c:943
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff815a0150-ffffffff815a01e5: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ce790)
Location: drivers/base/platform.c:957
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff815ce790-ffffffff815ce825: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e3220)
Location: drivers/base/platform.c:964
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff815e3220-ffffffff815e32b6: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a3d0)
Location: drivers/base/platform.c:965
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff8164a3d0-ffffffff8164a466: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685940)
Location: drivers/base/platform.c:963
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff81685940-ffffffff816859d8: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a55a0)
Location: drivers/base/platform.c:965
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff816a55a0-ffffffff816a5638: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de530)
Location: drivers/base/platform.c:1005
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff816de530-ffffffff816de5cc: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817027a0)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff817027a0-ffffffff8170283c: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bbff0)
Location: drivers/base/platform.c:1133
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff817bbff0-ffffffff817bc08c: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d0c00)
Location: drivers/base/platform.c:1379
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff817d0c00-ffffffff817d0c9c: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4620)
Location: drivers/base/platform.c:1378
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff817b4620-ffffffff817b46bc: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183d760)
Location: drivers/base/platform.c:1342
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff8183d760-ffffffff8183d7fc: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81980440)
Location: drivers/base/platform.c:1331
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff81980440-ffffffff81980509: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aedf10)
Location: drivers/base/platform.c:1331
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff81aedf10-ffffffff81aedfd9: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3c2a0)
Location: drivers/base/platform.c:1335
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff81b3c2a0-ffffffff81b3c369: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b93df0)
Location: drivers/base/platform.c:1335
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff81b93df0-ffffffff81b93eb9: platform_match (STB_LOCAL)
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
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ee0d0)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffff8000108ee0d0-ffff8000108ee1b4: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dbe4c)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
c09dbe4c-c09dbf18: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000986800)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
c000000000986800-c000000000986d6c: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe00058125a)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffe00058125a-ffffffe0005812fc: platform_match (STB_LOCAL)
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
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c7ef0)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff816c7ef0-ffffffff816c7f8c: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a31f0)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff816a31f0-ffffffff816a328c: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f6460)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff816f6460-ffffffff816f64fc: platform_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int platform_match(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710d00)
Location: drivers/base/platform.c:1070
Inline: True
Direct callers:
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:__platform_match
```
**Symbols:**

```
ffffffff81710d00-ffffffff81710d9c: platform_match (STB_LOCAL)
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
