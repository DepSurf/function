# Function: <code>sed_ioctl</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814603f0)
Location: block/sed-opal.c:2354
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814603f0-ffffffff81460ae8: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8148c2b0)
Location: block/sed-opal.c:2386
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff8148c2b0-ffffffff8148c9a8: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814c0fe0)
Location: block/sed-opal.c:2403
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814c0fe0-ffffffff814c1675: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d5390)
Location: block/sed-opal.c:2403
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814d5390-ffffffff814d5a29: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81501320)
Location: block/sed-opal.c:2413
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81501320-ffffffff81501ab8: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151f250)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff8151f250-ffffffff8151f9e8: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157f150)
Location: block/sed-opal.c:2623
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
```
**Symbols:**

```
ffffffff8157f150-ffffffff8157f824: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159c190)
Location: block/sed-opal.c:2623
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
```
**Symbols:**

```
ffffffff8159c190-ffffffff8159c864: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a2b60)
Location: block/sed-opal.c:2623
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
```
**Symbols:**

```
ffffffff815a2b60-ffffffff815a33ff: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:2623
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81cda5b4-ffffffff81cda5c9: sed_ioctl.cold (STB_LOCAL)
ffffffff8160b4b0-ffffffff8160bd5b: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:2623
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81e8e162-ffffffff81e8e177: sed_ioctl.cold (STB_LOCAL)
ffffffff816bf4a0-ffffffff816bfd25: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81780320)
Location: block/sed-opal.c:2745
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81780320-ffffffff81780ddb: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817c00b0)
Location: block/sed-opal.c:2983
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff817c00b0-ffffffff817c0c9e: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81806370)
Location: block/sed-opal.c:3209
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81806370-ffffffff81807284: sed_ioctl (STB_GLOBAL)
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
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010624a38)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffff800010624a38-ffff800010625178: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cc334)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
c07cc334-c07ccbc8: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c9840)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
c0000000007c9840-c0000000007ca180: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe0004591ae)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffe0004591ae-ffffffe000459868: sed_ioctl (STB_GLOBAL)
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
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81517830)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
```
**Symbols:**

```
ffffffff81517830-ffffffff81517fc8: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81507b40)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
```
**Symbols:**

```
ffffffff81507b40-ffffffff815082d8: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815138c0)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff815138c0-ffffffff81514058: sed_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sed_ioctl(struct opal_dev *dev, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152d080)
Location: block/sed-opal.c:2446
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff8152d080-ffffffff8152d818: sed_ioctl (STB_GLOBAL)
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
