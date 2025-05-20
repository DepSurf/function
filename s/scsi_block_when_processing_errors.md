# Function: <code>scsi_block_when_processing_errors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815aba10)
Location: drivers/scsi/scsi_error.c:311
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
```
**Symbols:**

```
ffffffff815aba10-ffffffff815abb28: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81603940)
Location: drivers/scsi/scsi_error.c:311
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81603940-ffffffff81603a57: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81633030)
Location: drivers/scsi/scsi_error.c:311
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81633030-ffffffff8163313b: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81647dc0)
Location: drivers/scsi/scsi_error.c:296
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81647dc0-ffffffff81647ec8: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816b0e40)
Location: drivers/scsi/scsi_error.c:311
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff816b0e40-ffffffff816b0f48: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ed170)
Location: drivers/scsi/scsi_error.c:333
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff816ed170-ffffffff816ed26f: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81710cd0)
Location: drivers/scsi/scsi_error.c:333
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81710cd0-ffffffff81710d94: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174c100)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8174c100-ffffffff8174c1c4: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81770280)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81770280-ffffffff81770344: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81831470)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81831470-ffffffff81831538: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81842080)
Location: drivers/scsi/scsi_error.c:342
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81842080-ffffffff81842148: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81825280)
Location: drivers/scsi/scsi_error.c:354
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81825280-ffffffff8182534d: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818b0b00)
Location: drivers/scsi/scsi_error.c:379
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff818b0b00-ffffffff818b0bd0: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff819fad50)
Location: drivers/scsi/scsi_error.c:378
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff819fad50-ffffffff819fae4c: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b78dc0)
Location: drivers/scsi/scsi_error.c:382
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81b78dc0-ffffffff81b78ebc: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcca50)
Location: drivers/scsi/scsi_error.c:382
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81bcca50-ffffffff81bccb4c: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c21680)
Location: drivers/scsi/scsi_error.c:384
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81c21680-ffffffff81c2177c: scsi_block_when_processing_errors (STB_GLOBAL)
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
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010971c20)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffff800010971c20-ffff800010971cf4: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a4805c)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
c0a4805c-c0a48140: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2cfd0)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
c000000000a2cfd0-c000000000a2d0e4: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005dc47e)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffe0005dc47e-ffffffe0005dc528: scsi_block_when_processing_errors (STB_GLOBAL)
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
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81724970)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81724970-ffffffff81724a34: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816fdda0)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff816fdda0-ffffffff816fde64: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81763740)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81763740-ffffffff81763804: scsi_block_when_processing_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_block_when_processing_errors(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8177eda0)
Location: drivers/scsi/scsi_error.c:334
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_open
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8177eda0-ffffffff8177ee5f: scsi_block_when_processing_errors (STB_GLOBAL)
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
