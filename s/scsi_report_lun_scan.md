# Function: <code>scsi_report_lun_scan</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, int bflags, int rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b2d10)
Location: drivers/scsi/scsi_scan.c:1295
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff815b2d10-ffffffff815b313f: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, int bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160b180)
Location: drivers/scsi/scsi_scan.c:1309
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff8160b180-ffffffff8160b595: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, int bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8163aa70)
Location: drivers/scsi/scsi_scan.c:1307
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff8163aa70-ffffffff8163ae39: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164f90f)
Location: drivers/scsi/scsi_scan.c:1290
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b8f0b)
Location: drivers/scsi/scsi_scan.c:1296
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f5241)
Location: drivers/scsi/scsi_scan.c:1296
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81717b9d)
Location: drivers/scsi/scsi_scan.c:1288
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff81752f50-ffffffff817532d1: scsi_report_lun_scan (STB_LOCAL)
ffffffff81753f71-ffffffff81753f8c: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff817771d0-ffffffff81777551: scsi_report_lun_scan (STB_LOCAL)
ffffffff817781f1-ffffffff8177820c: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1288
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff8183a0e0-ffffffff8183a461: scsi_report_lun_scan (STB_LOCAL)
ffffffff8183b149-ffffffff8183b164: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1288
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff8184aaa0-ffffffff8184ae21: scsi_report_lun_scan (STB_LOCAL)
ffffffff81c169f5-ffffffff81c16a10: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1307
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff8182de10-ffffffff8182e182: scsi_report_lun_scan (STB_LOCAL)
ffffffff81c08692-ffffffff81c086ad: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1316
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff818b9be0-ffffffff818b9f52: scsi_report_lun_scan (STB_LOCAL)
ffffffff81d0c777-ffffffff81d0c792: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1392
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff81a05550-ffffffff81a05915: scsi_report_lun_scan (STB_LOCAL)
ffffffff81ed5677-ffffffff81ed5691: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b84250)
Location: drivers/scsi/scsi_scan.c:1391
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff81b84250-ffffffff81b84643: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd7fa0)
Location: drivers/scsi/scsi_scan.c:1398
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff81bd7fa0-ffffffff81bd83bb: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2cc70)
Location: drivers/scsi/scsi_scan.c:1398
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff81c2cc70-ffffffff81c2d08b: scsi_report_lun_scan (STB_LOCAL)
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
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097b510)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffff80001097b510-ffff80001097b8e8: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4f2dc)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
c0a4f2dc-c0a4f728: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a36720)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
c000000000a36720-c000000000a36c2c: scsi_report_lun_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e257c)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffe0005e257c-ffffffe0005e28f2: scsi_report_lun_scan (STB_LOCAL)
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
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff8172b8c0-ffffffff8172bc41: scsi_report_lun_scan (STB_LOCAL)
ffffffff8172c8e1-ffffffff8172c8fc: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff81704ce0-ffffffff81705061: scsi_report_lun_scan (STB_LOCAL)
ffffffff81705d01-ffffffff81705d1c: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff8176a690-ffffffff8176aa11: scsi_report_lun_scan (STB_LOCAL)
ffffffff8176b6b1-ffffffff8176b6cc: scsi_report_lun_scan.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_report_lun_scan(struct scsi_target *starget, blist_flags_t bflags, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1289
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff81785de0-ffffffff81786161: scsi_report_lun_scan (STB_LOCAL)
ffffffff81786df1-ffffffff81786e0c: scsi_report_lun_scan.cold (STB_LOCAL)
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
