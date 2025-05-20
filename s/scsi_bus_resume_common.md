# Function: <code>scsi_bus_resume_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff815b8fb0)
Location: drivers/scsi/scsi_pm.c:126
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff815b8f80-ffffffff815b8fac: scsi_bus_resume_common.part.1 (STB_LOCAL)
ffffffff815b8fb0-ffffffff815b9047: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816117b0)
Location: drivers/scsi/scsi_pm.c:126
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff816117b0-ffffffff816118d2: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81641040)
Location: drivers/scsi/scsi_pm.c:126
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff81641040-ffffffff81641162: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81655930)
Location: drivers/scsi/scsi_pm.c:126
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff81655930-ffffffff81655a47: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816beee0)
Location: drivers/scsi/scsi_pm.c:126
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff816beee0-ffffffff816beff7: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816fb4f0)
Location: drivers/scsi/scsi_pm.c:126
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff816fb4f0-ffffffff816fb609: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8171df70)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff8171df70-ffffffff8171e027: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff817596a0)
Location: drivers/scsi/scsi_pm.c:142
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff817596a0-ffffffff8175975c: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8177d5c0)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff8177d5c0-ffffffff8177d67c: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81840a30)
Location: drivers/scsi/scsi_pm.c:147
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff81840a30-ffffffff81840aec: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81850f70)
Location: drivers/scsi/scsi_pm.c:141
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff81850f70-ffffffff8185102c: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81834000)
Location: drivers/scsi/scsi_pm.c:141
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff81834000-ffffffff818340ba: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff818c0000)
Location: drivers/scsi/scsi_pm.c:141
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff818c0000-ffffffff818c00ba: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81a0c835)
Location: drivers/scsi/scsi_pm.c:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81b8c705)
Location: drivers/scsi/scsi_pm.c:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81be0575)
Location: drivers/scsi/scsi_pm.c:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
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
In drivers/scsi/scsi_pm.c (ffffffff81c355a5)
Location: drivers/scsi/scsi_pm.c:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
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
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffff800010983770)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffff800010983770-ffff800010983864: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (c0a56020)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
c0a56020-c0a56104: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (c000000000a402b0)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
c000000000a402b0-c000000000a40444: scsi_bus_resume_common (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81731cb0)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff81731cb0-ffffffff81731d6c: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8170b0d0)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff8170b0d0-ffffffff8170b18c: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81770a80)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff81770a80-ffffffff81770b3c: scsi_bus_resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int scsi_bus_resume_common(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8178c220)
Location: drivers/scsi/scsi_pm.c:141
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
```
**Symbols:**

```
ffffffff8178c220-ffffffff8178c2dc: scsi_bus_resume_common (STB_LOCAL)
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
