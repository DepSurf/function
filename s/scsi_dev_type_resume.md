# Function: <code>scsi_dev_type_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff815b8f80)
Location: drivers/scsi/scsi_pm.c:70
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff815b8f80-ffffffff815b8fac: scsi_dev_type_resume.part.2 (STB_LOCAL)
ffffffff815b90b0-ffffffff815b9123: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816119a0)
Location: drivers/scsi/scsi_pm.c:70
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff816119a0-ffffffff81611a26: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81641230)
Location: drivers/scsi/scsi_pm.c:70
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff81641230-ffffffff816412b6: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81655b10)
Location: drivers/scsi/scsi_pm.c:70
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff81655b10-ffffffff81655b94: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816bf0c0)
Location: drivers/scsi/scsi_pm.c:70
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff816bf0c0-ffffffff816bf147: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816fb6d0)
Location: drivers/scsi/scsi_pm.c:70
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff816fb6d0-ffffffff816fb762: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8171e090)
Location: drivers/scsi/scsi_pm.c:71
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff8171e090-ffffffff8171e144: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff817597c0)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff817597c0-ffffffff81759871: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8177d6e0)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff8177d6e0-ffffffff8177d787: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81840cc0)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff81840cc0-ffffffff81840d8c: scsi_dev_type_resume.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81851200)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff81851200-ffffffff818512a4: scsi_dev_type_resume.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81834290)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff81834290-ffffffff81834334: scsi_dev_type_resume.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff818c0290)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff818c0290-ffffffff818c0331: scsi_dev_type_resume.isra.0 (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffff800010983910)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffff800010983910-ffff8000109839d4: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (c0a56170)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
c0a56170-c0a56230: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (c000000000a404b0)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
c000000000a404b0-c000000000a405c4: scsi_dev_type_resume (STB_LOCAL)
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
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81731dd0)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff81731dd0-ffffffff81731e77: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8170b1f0)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff8170b1f0-ffffffff8170b297: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81770ba0)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff81770ba0-ffffffff81770c47: scsi_dev_type_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int scsi_dev_type_resume(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8178c340)
Location: drivers/scsi/scsi_pm.c:72
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:async_sdev_restore
  - drivers/scsi/scsi_pm.c:async_sdev_thaw
  - drivers/scsi/scsi_pm.c:async_sdev_resume
```
**Symbols:**

```
ffffffff8178c340-ffffffff8178c3e7: scsi_dev_type_resume (STB_LOCAL)
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
