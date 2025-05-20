# Function: <code>talk_to_blkback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81575950)
Location: drivers/block/xen-blkfront.c:1460
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81575950-ffffffff81576211: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815c94a0)
Location: drivers/block/xen-blkfront.c:1756
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff815c94a0-ffffffff815c9d1f: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f61f0)
Location: drivers/block/xen-blkfront.c:1755
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff815f61f0-ffffffff815f6a3b: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160a520)
Location: drivers/block/xen-blkfront.c:1768
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff8160a520-ffffffff8160ad82: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81672df0)
Location: drivers/block/xen-blkfront.c:1768
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81672df0-ffffffff81673652: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816ae8d0)
Location: drivers/block/xen-blkfront.c:1768
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff816ae8d0-ffffffff816af26d: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816d30a0)
Location: drivers/block/xen-blkfront.c:1773
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff816d30a0-ffffffff816d3a97: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1773
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff8170e730-ffffffff8170f56b: talk_to_blkback (STB_LOCAL)
ffffffff8170fe43-ffffffff8170fe58: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1773
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81732a30-ffffffff8173386b: talk_to_blkback (STB_LOCAL)
ffffffff8173412d-ffffffff81734142: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1783
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff817f0230-ffffffff817f0bc2: talk_to_blkback (STB_LOCAL)
ffffffff817f16ce-ffffffff817f16e3: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1784
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81804b40-ffffffff818054e0: talk_to_blkback (STB_LOCAL)
ffffffff81c0fdb1-ffffffff81c0fdc6: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1784
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff817e96e0-ffffffff817ea089: talk_to_blkback (STB_LOCAL)
ffffffff81c01f55-ffffffff81c01f6a: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1780
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81875e60-ffffffff818767b2: talk_to_blkback (STB_LOCAL)
ffffffff81d05caa-ffffffff81d05cd8: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1760
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff819bdff0-ffffffff819be978: talk_to_blkback (STB_LOCAL)
ffffffff81ece5ab-ffffffff81ece5ec: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1769
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81b336f0-ffffffff81b340a7: talk_to_blkback (STB_LOCAL)
ffffffff82099c4f-ffffffff82099c99: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1770
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81b86c40-ffffffff81b875b0: talk_to_blkback (STB_LOCAL)
ffffffff8211ad6a-ffffffff8211adb4: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1770
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81bdaaf0-ffffffff81bdb460: talk_to_blkback (STB_LOCAL)
ffffffff821f8bf0-ffffffff821f8c3a: talk_to_blkback.cold (STB_LOCAL)
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
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010927618)
Location: drivers/block/xen-blkfront.c:1773
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffff800010927618-ffff8000109282c0: talk_to_blkback (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1798
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_restore
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff816f89e0-ffffffff816f981b: talk_to_blkback (STB_LOCAL)
ffffffff816fa1c1-ffffffff816fa1d6: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1773
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81725ef0-ffffffff81726d2b: talk_to_blkback (STB_LOCAL)
ffffffff817275ed-ffffffff81727602: talk_to_blkback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int talk_to_blkback(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1773
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81741340-ffffffff8174217b: talk_to_blkback (STB_LOCAL)
ffffffff81742a3a-ffffffff81742a4f: talk_to_blkback.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
