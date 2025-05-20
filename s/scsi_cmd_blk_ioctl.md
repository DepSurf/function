# Function: <code>scsi_cmd_blk_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff813cc9d0)
Location: block/scsi_ioctl.c:742
Inline: True
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff813cc9d0-ffffffff813cca1b: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81410d30)
Location: block/scsi_ioctl.c:742
Inline: True
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81410d30-ffffffff81410d7b: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8142c0c0)
Location: block/scsi_ioctl.c:745
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff8142c0c0-ffffffff8142c10b: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81443e90)
Location: block/scsi_ioctl.c:743
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81443e90-ffffffff81443edb: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81470920)
Location: block/scsi_ioctl.c:743
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81470920-ffffffff8147096b: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814a4b30)
Location: block/scsi_ioctl.c:701
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff814a4b30-ffffffff814a4b91: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814bf5f0)
Location: block/scsi_ioctl.c:701
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff814bf5f0-ffffffff814bf651: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ede40)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff814ede40-ffffffff814edea1: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815072b0)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff815072b0-ffffffff81507311: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81568030)
Location: block/scsi_ioctl.c:867
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81568030-ffffffff81568091: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81582d90)
Location: block/scsi_ioctl.c:858
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81582d90-ffffffff81582df1: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81589bc0)
Location: block/scsi_ioctl.c:854
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81589bc0-ffffffff81589c21: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffff800010609670)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffff800010609670-ffff8000106096e8: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c07b4b80)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
c07b4b80-c07b4bf4: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c0000000007a5b70)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
c0000000007a5b70-c0000000007a5c34: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffe000442fe2)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffe000442fe2-ffffffe000443042: scsi_cmd_blk_ioctl (STB_GLOBAL)
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
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ff890)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff814ff890-ffffffff814ff8f1: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814efda0)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff814efda0-ffffffff814efe01: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814fb920)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff814fb920-ffffffff814fb981: scsi_cmd_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_cmd_blk_ioctl(struct block_device *bd, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815149d0)
Location: block/scsi_ioctl.c:687
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff815149d0-ffffffff81514a31: scsi_cmd_blk_ioctl (STB_GLOBAL)
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
