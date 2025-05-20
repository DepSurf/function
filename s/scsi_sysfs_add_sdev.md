# Function: <code>scsi_sysfs_add_sdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff815b58e0)
Location: drivers/scsi/scsi_sysfs.c:1028
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff815b58e0-ffffffff815b5b78: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e000)
Location: drivers/scsi/scsi_sysfs.c:1201
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8160e000-ffffffff8160e288: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8163d8a0)
Location: drivers/scsi/scsi_sysfs.c:1201
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8163d8a0-ffffffff8163db2c: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff816523f0)
Location: drivers/scsi/scsi_sysfs.c:1203
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816523f0-ffffffff8165267e: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff816bb810)
Location: drivers/scsi/scsi_sysfs.c:1254
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816bb810-ffffffff816bba65: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff816f7c10)
Location: drivers/scsi/scsi_sysfs.c:1270
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816f7c10-ffffffff816f7eb7: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8171a510)
Location: drivers/scsi/scsi_sysfs.c:1276
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8171a510-ffffffff8171a7b7: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1288
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81756459-ffffffff81756475: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff81755c00-ffffffff81755e88: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff8177a6f9-ffffffff8177a715: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff81779e80-ffffffff8177a108: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1316
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff8183d839-ffffffff8183d855: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff8183ced0-ffffffff8183d16b: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1327
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81c16a8c-ffffffff81c16aa8: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff8184d6d0-ffffffff8184d96b: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1333
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81c08753-ffffffff81c08769: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff81830b80-ffffffff81830e10: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1351
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81d0c838-ffffffff81d0c84e: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff818bcbb0-ffffffff818bce50: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1370
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81ed5734-ffffffff81ed574a: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff81a08dd0-ffffffff81a08ff6: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81b881a0)
Location: drivers/scsi/scsi_sysfs.c:1364
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81b881a0-ffffffff81b883e9: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc080)
Location: drivers/scsi/scsi_sysfs.c:1394
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81bdc080-ffffffff81bdc2c7: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81c30db0)
Location: drivers/scsi/scsi_sysfs.c:1394
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81c30db0-ffffffff81c30ff7: scsi_sysfs_add_sdev (STB_GLOBAL)
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
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffff80001097f588)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffff80001097f588-ffff80001097f7fc: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (c0a523a8)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
c0a523a8-c0a525f4: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (c000000000a3afc0)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
c000000000a3afc0-c000000000a3b330: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e57ee)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffe0005e57ee-ffffffe0005e5a34: scsi_sysfs_add_sdev (STB_GLOBAL)
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
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff8172ede9-ffffffff8172ee05: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff8172e570-ffffffff8172e7f8: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81708209-ffffffff81708225: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff81707990-ffffffff81707c18: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff8176dbb9-ffffffff8176dbd5: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff8176d340-ffffffff8176d5c8: scsi_sysfs_add_sdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_sysfs_add_sdev(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (0)
Location: drivers/scsi/scsi_sysfs.c:1297
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
**Symbols:**

```
ffffffff81789359-ffffffff81789375: scsi_sysfs_add_sdev.cold (STB_LOCAL)
ffffffff81788ae0-ffffffff81788d68: scsi_sysfs_add_sdev (STB_GLOBAL)
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
