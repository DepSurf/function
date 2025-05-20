# Function: <code>scsi_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff815a8e10)
Location: drivers/scsi/scsi_ioctl.c:199
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff815a8e10-ffffffff815a91ba: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81600cc0)
Location: drivers/scsi/scsi_ioctl.c:199
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81600cc0-ffffffff8160109a: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff816303b0)
Location: drivers/scsi/scsi_ioctl.c:199
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff816303b0-ffffffff8163078a: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81645130)
Location: drivers/scsi/scsi_ioctl.c:199
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81645130-ffffffff816454fd: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff816ae0c0)
Location: drivers/scsi/scsi_ioctl.c:201
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff816ae0c0-ffffffff816ae493: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:201
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff816ea865-ffffffff816ea886: scsi_ioctl.cold.6 (STB_LOCAL)
ffffffff816ea4c0-ffffffff816ea865: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:201
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8170e31f-ffffffff8170e340: scsi_ioctl.cold.6 (STB_LOCAL)
ffffffff8170df80-ffffffff8170e31f: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81749ab1-ffffffff81749afa: scsi_ioctl.cold (STB_LOCAL)
ffffffff81749740-ffffffff81749ab1: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8176dbfc-ffffffff8176dc45: scsi_ioctl.cold (STB_LOCAL)
ffffffff8176d870-ffffffff8176dbfc: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81830160)
Location: drivers/scsi/scsi_ioctl.c:273
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81830160-ffffffff818301b5: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81840e20)
Location: drivers/scsi/scsi_ioctl.c:273
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81840e20-ffffffff81840e75: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81824010)
Location: drivers/scsi/scsi_ioctl.c:273
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81824010-ffffffff81824065: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, struct gendisk *disk, fmode_t mode, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:894
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81d0c168-ffffffff81d0c1e6: scsi_ioctl.cold (STB_LOCAL)
ffffffff818af420-ffffffff818af8ff: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, fmode_t mode, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:876
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81ed5097-ffffffff81ed50fb: scsi_ioctl.cold (STB_LOCAL)
ffffffff819fa350-ffffffff819fa896: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, fmode_t mode, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81b782e0)
Location: drivers/scsi/scsi_ioctl.c:860
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81b782e0-ffffffff81b78889: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, bool open_for_write, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcbf80)
Location: drivers/scsi/scsi_ioctl.c:863
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81bcbf80-ffffffff81bcc519: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, bool open_for_write, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81c20bb0)
Location: drivers/scsi/scsi_ioctl.c:863
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81c20bb0-ffffffff81c21149: scsi_ioctl (STB_GLOBAL)
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
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffff800010970070)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffff800010970070-ffff800010970af8: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (c0a4520c)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c0a4520c-c0a4574c: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (c000000000a297e0)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c000000000a297e0-c000000000a29e70: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffe0005d9ec6)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffe0005d9ec6-ffffffe0005da1e6: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff817222ec-ffffffff81722335: scsi_ioctl.cold (STB_LOCAL)
ffffffff81721f60-ffffffff817222ec: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff816fb71c-ffffffff816fb765: scsi_ioctl.cold (STB_LOCAL)
ffffffff816fb390-ffffffff816fb71c: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff817610bc-ffffffff81761105: scsi_ioctl.cold (STB_LOCAL)
ffffffff81760d30-ffffffff817610bc: scsi_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (0)
Location: drivers/scsi/scsi_ioctl.c:202
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sr.c:sr_block_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8177c71c-ffffffff8177c765: scsi_ioctl.cold (STB_LOCAL)
ffffffff8177c390-ffffffff8177c71c: scsi_ioctl (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param added. </b>
<code>fmode_t mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, cmd, arg</code> ➡️ <code>sdev, disk, mode, cmd, arg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, disk, mode, cmd, arg</code> ➡️ <code>sdev, mode, cmd, arg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_for_write</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
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
