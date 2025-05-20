# Function: <code>scsi_scan_host_selected</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, int rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b3bb0)
Location: drivers/scsi/scsi_scan.c:1652
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff815b3bb0-ffffffff815b3d07: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160c010)
Location: drivers/scsi/scsi_scan.c:1682
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff8160c010-ffffffff8160c15b: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8163b8b0)
Location: drivers/scsi/scsi_scan.c:1676
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff8163b8b0-ffffffff8163b9fb: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81650330)
Location: drivers/scsi/scsi_scan.c:1659
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81650330-ffffffff81650479: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b9640)
Location: drivers/scsi/scsi_scan.c:1665
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff816b9640-ffffffff816b9789: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f5970)
Location: drivers/scsi/scsi_scan.c:1665
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff816f5970-ffffffff816f5af0: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817182b0)
Location: drivers/scsi/scsi_scan.c:1657
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff817182b0-ffffffff817183fd: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81753fa7-ffffffff81753fd5: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff817539f0-ffffffff81753b09: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81778227-ffffffff81778255: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff81777c70-ffffffff81777d89: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1657
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff8183b17f-ffffffff8183b1ad: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff8183abd0-ffffffff8183ace9: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1657
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81c16a2b-ffffffff81c16a59: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff8184b5a0-ffffffff8184b6b9: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1675
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81c086c8-ffffffff81c086f6: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff8182e910-ffffffff8182ea29: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1684
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81d0c7ad-ffffffff81d0c7db: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff818ba6e0-ffffffff818ba7f9: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1760
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81ed56ac-ffffffff81ed56da: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff81a06100-ffffffff81a06231: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b84ec0)
Location: drivers/scsi/scsi_scan.c:1760
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81b84ec0-ffffffff81b8501f: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd8c40)
Location: drivers/scsi/scsi_scan.c:1772
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81bd8c40-ffffffff81bd8d9f: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2d940)
Location: drivers/scsi/scsi_scan.c:1789
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81c2d940-ffffffff81c2da9f: scsi_scan_host_selected (STB_GLOBAL)
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
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097c660)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffff80001097c660-ffff80001097c7d4: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4ff6c)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
c0a4ff6c-c0a500f0: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a377d0)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
c000000000a377d0-c000000000a379bc: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e332a)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffe0005e332a-ffffffe0005e345c: scsi_scan_host_selected (STB_GLOBAL)
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
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff8172c917-ffffffff8172c945: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff8172c360-ffffffff8172c479: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81705d37-ffffffff81705d65: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff81705780-ffffffff81705899: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff8176b6e7-ffffffff8176b715: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff8176b130-ffffffff8176b249: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_scan_host_selected(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1658
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_proc.c:proc_scsi_write
```
**Symbols:**

```
ffffffff81786e27-ffffffff81786e55: scsi_scan_host_selected.cold (STB_LOCAL)
ffffffff81786880-ffffffff81786999: scsi_scan_host_selected (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rescan</code> ➡️ <code>enum scsi_scan_mode rescan</code>
</li>
</ul>
</details>
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
