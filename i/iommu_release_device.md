# Function: <code>iommu_release_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff8152cab0)
Location: drivers/iommu/iommu-sysfs.c:35
Inline: False
```
**Symbols:**

```
ffffffff8152cab0-ffffffff8152cac0: iommu_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff8157fed0)
Location: drivers/iommu/iommu-sysfs.c:35
Inline: False
```
**Symbols:**

```
ffffffff8157fed0-ffffffff8157fee0: iommu_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff815aca60)
Location: drivers/iommu/iommu-sysfs.c:35
Inline: False
```
**Symbols:**

```
ffffffff815aca60-ffffffff815aca70: iommu_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff815c2650)
Location: drivers/iommu/iommu-sysfs.c:35
Inline: False
```
**Symbols:**

```
ffffffff815c2650-ffffffff815c2660: iommu_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81628e30)
Location: drivers/iommu/iommu-sysfs.c:35
Inline: False
```
**Symbols:**

```
ffffffff81628e30-ffffffff81628e40: iommu_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81663b60)
Location: drivers/iommu/iommu-sysfs.c:35
Inline: False
```
**Symbols:**

```
ffffffff81663b60-ffffffff81663b70: iommu_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167ebd5)
Location: drivers/iommu/iommu.c:127
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff81680730-ffffffff8168075d: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b7ed0)
Location: drivers/iommu/iommu.c:140
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff816b7ed0-ffffffff816b7f15: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816dac30)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff816dac30-ffffffff816dac75: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f390)
Location: drivers/iommu/iommu.c:290
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:remove_iommu_group
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8178f390-ffffffff8178f43b: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bc040)
Location: drivers/iommu/iommu.c:296
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:remove_iommu_group
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff817bc040-ffffffff817bc0eb: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f200)
Location: drivers/iommu/iommu.c:303
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:remove_iommu_group
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8179f200-ffffffff8179f2ab: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818281d0)
Location: drivers/iommu/iommu.c:323
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:remove_iommu_group
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff818281d0-ffffffff81828261: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81968170)
Location: drivers/iommu/iommu.c:329
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff81968170-ffffffff8196821d: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad1db0)
Location: drivers/iommu/iommu.c:455
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff81ad1db0-ffffffff81ad1e62: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1ed60)
Location: drivers/iommu/iommu.c:499
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff81b1ed60-ffffffff81b1eec9: iommu_release_device (STB_LOCAL)
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
In drivers/iommu/iommu.c (ffffffff81b76452)
Location: drivers/iommu/iommu.c:661
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:remove_iommu_group
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
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c6b00)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffff8000108c6b00-ffff8000108c6b4c: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bdb10)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
c09bdb10-c09bdb58: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096d660)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
c00000000096d660-c00000000096d6d4: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0680)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff816a0680-ffffffff816a06c5: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e070)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff8167e070-ffffffff8167e0b5: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce8f0)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff816ce8f0-ffffffff816ce935: iommu_release_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_release_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8e60)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:remove_iommu_group
```
**Symbols:**

```
ffffffff816e8e60-ffffffff816e8ea5: iommu_release_device (STB_GLOBAL)
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
