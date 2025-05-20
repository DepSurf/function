# Function: <code>scsi_test_unit_ready</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr_external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815af570)
Location: drivers/scsi/scsi_lib.c:2529
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff815af570-ffffffff815af6b1: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr_external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816077e0)
Location: drivers/scsi/scsi_lib.c:2402
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff816077e0-ffffffff81607922: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr_external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81636eb0)
Location: drivers/scsi/scsi_lib.c:2443
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81636eb0-ffffffff81636ffa: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649730)
Location: drivers/scsi/scsi_lib.c:2523
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81649730-ffffffff81649802: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2950)
Location: drivers/scsi/scsi_lib.c:2601
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff816b2950-ffffffff816b2a22: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816eeac0)
Location: drivers/scsi/scsi_lib.c:2617
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff816eeac0-ffffffff816eeb96: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81712660)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81712660-ffffffff81712736: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174dfd0)
Location: drivers/scsi/scsi_lib.c:2161
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff8174dfd0-ffffffff8174e0a6: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772180)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81772180-ffffffff81772256: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818346b0)
Location: drivers/scsi/scsi_lib.c:2189
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff818346b0-ffffffff81834786: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81845090)
Location: drivers/scsi/scsi_lib.c:2197
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81845090-ffffffff81845166: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828220)
Location: drivers/scsi/scsi_lib.c:2214
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81828220-ffffffff818282f6: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b3b60)
Location: drivers/scsi/scsi_lib.c:2207
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff818b3b60-ffffffff818b3c36: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00990)
Location: drivers/scsi/scsi_lib.c:2273
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81a00990-ffffffff81a00a78: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7f030)
Location: drivers/scsi/scsi_lib.c:2278
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81b7f030-ffffffff81b7f118: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd2fd0)
Location: drivers/scsi/scsi_lib.c:2291
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81bd2fd0-ffffffff81bd30d9: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c27c40)
Location: drivers/scsi/scsi_lib.c:2288
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81c27c40-ffffffff81c27d55: scsi_test_unit_ready (STB_GLOBAL)
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
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010975958)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffff800010975958-ffff800010975a78: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a49ed0)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
c0a49ed0-c0a49ff8: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a2f7b0)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
c000000000a2f7b0-c000000000a2f914: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005ddec8)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffe0005ddec8-ffffffe0005ddf80: scsi_test_unit_ready (STB_GLOBAL)
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
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81726870)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81726870-ffffffff81726946: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ffca0)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/storvsc_drv.c:storvsc_host_scan
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff816ffca0-ffffffff816ffd76: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81765640)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81765640-ffffffff81765716: scsi_test_unit_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_test_unit_ready(struct scsi_device *sdev, int timeout, int retries, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81780cd0)
Location: drivers/scsi/scsi_lib.c:2208
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_drive_status
```
**Symbols:**

```
ffffffff81780cd0-ffffffff81780da6: scsi_test_unit_ready (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scsi_sense_hdr *sshdr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct scsi_sense_hdr *sshdr_external</code>
</li>
</ul>
</details>
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
