# Function: <code>scsi_change_queue_depth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a5b30)
Location: drivers/scsi/scsi.c:617
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
**Symbols:**

```
ffffffff815a5b30-ffffffff815a5b4a: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fd940)
Location: drivers/scsi/scsi.c:617
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff815fd940-ffffffff815fd95a: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162dcc0)
Location: drivers/scsi/scsi.c:617
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8162dcc0-ffffffff8162dced: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81643100)
Location: drivers/scsi/scsi.c:258
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81643100-ffffffff8164312d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac110)
Location: drivers/scsi/scsi.c:258
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff816ac110-ffffffff816ac13d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8630)
Location: drivers/scsi/scsi.c:258
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff816e8630-ffffffff816e865d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c130)
Location: drivers/scsi/scsi.c:258
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8170c130-ffffffff8170c15d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747860)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81747860-ffffffff8174788d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176b9b0)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8176b9b0-ffffffff8176b9dd: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e23e)
Location: drivers/scsi/scsi.c:224
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8182dc80-ffffffff8182dcb0: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f27e)
Location: drivers/scsi/scsi.c:224
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8183ecc0-ffffffff8183ecf0: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818225f2)
Location: drivers/scsi/scsi.c:233
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81821ea0-ffffffff81821efa: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818acf32)
Location: drivers/scsi/scsi.c:226
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff818ac7e0-ffffffff818ac835: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7cce)
Location: drivers/scsi/scsi.c:217
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff819f75e0-ffffffff819f763d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b755be)
Location: drivers/scsi/scsi.c:217
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81b743b0-ffffffff81b7440d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc8eee)
Location: drivers/scsi/scsi.c:217
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/virtio_scsi.c:virtscsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-sata.c:ata_change_queue_depth
```
**Symbols:**

```
ffffffff81bc7b90-ffffffff81bc7bed: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1ddde)
Location: drivers/scsi/scsi.c:217
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/virtio_scsi.c:virtscsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-sata.c:ata_change_queue_depth
```
**Symbols:**

```
ffffffff81c1c700-ffffffff81c1c75d: scsi_change_queue_depth (STB_GLOBAL)
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
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096d8c8)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffff80001096d8c8-ffff80001096d914: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a432e0)
Location: drivers/scsi/scsi.c:238
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
c0a432e0-c0a43328: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a26ba0)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
c000000000a26ba0-c000000000a26c04: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d8228)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffe0005d8228-ffffffe0005d826c: scsi_change_queue_depth (STB_GLOBAL)
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
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff817200a0)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff817200a0-ffffffff817200cd: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f94d0)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/storvsc_drv.c:storvsc_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff816f94d0-ffffffff816f94fd: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175ee70)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/virtio_scsi.c:virtscsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8175ee70-ffffffff8175ee9d: scsi_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int scsi_change_queue_depth(struct scsi_device *sdev, int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a4d0)
Location: drivers/scsi/scsi.c:238
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8177a4d0-ffffffff8177a4fd: scsi_change_queue_depth (STB_GLOBAL)
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
