# Function: <code>__ata_change_queue_depth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815d39d0)
Location: drivers/ata/libata-scsi.c:1271
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff815d39d0-ffffffff815d3ade: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8162d480)
Location: drivers/ata/libata-scsi.c:1337
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff8162d480-ffffffff8162d58e: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8165e5b0)
Location: drivers/ata/libata-scsi.c:1415
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff8165e5b0-ffffffff8165e6be: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81672f90)
Location: drivers/ata/libata-scsi.c:1406
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81672f90-ffffffff8167308b: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816dc580)
Location: drivers/ata/libata-scsi.c:1407
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff816dc580-ffffffff816dc67b: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81718d00)
Location: drivers/ata/libata-scsi.c:1410
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81718d00-ffffffff81718de6: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8173b3b0)
Location: drivers/ata/libata-scsi.c:1405
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff8173b3b0-ffffffff8173b496: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81777055)
Location: drivers/ata/libata-scsi.c:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81775f90-ffffffff81776069: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff81777030-ffffffff8177704d: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8179afb5)
Location: drivers/ata/libata-scsi.c:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81799ef0-ffffffff81799fc9: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff8179af90-ffffffff8179afad: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81868635)
Location: drivers/ata/libata-sata.c:1012
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81868070-ffffffff81868149: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff81868150-ffffffff8186816d: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81877445)
Location: drivers/ata/libata-sata.c:1012
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81876e80-ffffffff81876f59: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff81876f60-ffffffff81876f7d: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81859670)
Location: drivers/ata/libata-sata.c:1012
Inline: True
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81859670-ffffffff81859761: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818e8220)
Location: drivers/ata/libata-sata.c:1024
Inline: True
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff818e8220-ffffffff818e8311: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81a39cd0)
Location: drivers/ata/libata-sata.c:1030
Inline: True
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81a39cd0-ffffffff81a39dd9: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
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
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffff8000109a5840)
Location: drivers/ata/libata-scsi.c:1388
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffff8000109a5840-ffff8000109a59a8: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a75a00)
Location: drivers/ata/libata-scsi.c:1388
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
c0a75a00-c0a75af0: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a6b800)
Location: drivers/ata/libata-scsi.c:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
c000000000a69990-c000000000a69acc: __ata_change_queue_depth.part.0 (STB_LOCAL)
c000000000a6b7b0-c000000000a6b7e8: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe0006046a0)
Location: drivers/ata/libata-scsi.c:1388
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffe0006046a0-ffffffe000604792: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817600a5)
Location: drivers/ata/libata-scsi.c:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff8175efe0-ffffffff8175f0b9: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff81760080-ffffffff8176009d: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8173ff05)
Location: drivers/ata/libata-scsi.c:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff8173ee60-ffffffff8173ef39: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff8173fee0-ffffffff8173fefd: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8178fe35)
Location: drivers/ata/libata-scsi.c:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff8178ed70-ffffffff8178ee49: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff8178fe10-ffffffff8178fe2d: __ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817a9c75)
Location: drivers/ata/libata-scsi.c:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff817a8ea0-ffffffff817a8f79: __ata_change_queue_depth.part.0 (STB_LOCAL)
ffffffff817a9c50-ffffffff817a9c6d: __ata_change_queue_depth (STB_GLOBAL)
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
