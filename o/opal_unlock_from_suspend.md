# Function: <code>opal_unlock_from_suspend</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145e600)
Location: block/sed-opal.c:2323
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff8145e600-ffffffff8145e6e2: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8148a3e0)
Location: block/sed-opal.c:2350
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff8148a3e0-ffffffff8148a5a4: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bf0f0)
Location: block/sed-opal.c:2367
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff814bf0f0-ffffffff814bf2aa: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d0670)
Location: block/sed-opal.c:2367
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff814d0670-ffffffff814d0822: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814fe770)
Location: block/sed-opal.c:2377
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff814fe770-ffffffff814fe90f: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151c6c0)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff8151c6c0-ffffffff8151c85f: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8157ed80)
Location: block/sed-opal.c:2522
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff8157ed80-ffffffff8157eeec: opal_unlock_from_suspend.part.0 (STB_LOCAL)
ffffffff8157eef0-ffffffff8157ef10: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8159bdc0)
Location: block/sed-opal.c:2522
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff8159bdc0-ffffffff8159bf2c: opal_unlock_from_suspend.part.0 (STB_LOCAL)
ffffffff8159bf30-ffffffff8159bf50: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a28c0)
Location: block/sed-opal.c:2522
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff815a28c0-ffffffff815a2a5f: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8160b26f)
Location: block/sed-opal.c:2522
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff81cda582-ffffffff81cda5b4: opal_unlock_from_suspend.cold (STB_LOCAL)
ffffffff8160b200-ffffffff8160b3a4: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff816bf25b)
Location: block/sed-opal.c:2522
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume_system
```
**Symbols:**

```
ffffffff81e8e130-ffffffff81e8e162: opal_unlock_from_suspend.cold (STB_LOCAL)
ffffffff816bf1e0-ffffffff816bf38d: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81780040)
Location: block/sed-opal.c:2627
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume_system
```
**Symbols:**

```
ffffffff81780040-ffffffff817801e7: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bfdd0)
Location: block/sed-opal.c:2845
Inline: True
```
**Symbols:**

```
ffffffff817bfdd0-ffffffff817bff77: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81804770)
Location: block/sed-opal.c:3068
Inline: True
```
**Symbols:**

```
ffffffff81804770-ffffffff81804917: opal_unlock_from_suspend (STB_GLOBAL)
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
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625178)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffff800010625178-ffff800010625324: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07ccbc8)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
c07ccbc8-c07ccd90: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c5d40)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
c0000000007c5d40-c0000000007c6000: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe00045641c)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffe00045641c-ffffffe000456592: opal_unlock_from_suspend (STB_GLOBAL)
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
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81514ca0)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff81514ca0-ffffffff81514e3f: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81504fb0)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff81504fb0-ffffffff8150514f: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81510d30)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff81510d30-ffffffff81510ecf: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool opal_unlock_from_suspend(struct opal_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152a4f0)
Location: block/sed-opal.c:2407
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_resume
```
**Symbols:**

```
ffffffff8152a4f0-ffffffff8152a68f: opal_unlock_from_suspend (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
