# Function: <code>scsi_device_lookup_by_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a6a20)
Location: drivers/scsi/scsi.c:1061
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff815a6a20-ffffffff815a6aca: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fecb0)
Location: drivers/scsi/scsi.c:1076
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff815fecb0-ffffffff815fed5b: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162e300)
Location: drivers/scsi/scsi.c:1079
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8162e300-ffffffff8162e3ab: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816436f0)
Location: drivers/scsi/scsi.c:720
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816436f0-ffffffff8164379c: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac800)
Location: drivers/scsi/scsi.c:700
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816ac800-ffffffff816ac8ac: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8d30)
Location: drivers/scsi/scsi.c:700
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816e8d30-ffffffff816e8de0: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c820)
Location: drivers/scsi/scsi.c:700
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8170c820-ffffffff8170c8c7: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747f10)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81747f10-ffffffff81747fba: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176c060)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8176c060-ffffffff8176c10a: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e270)
Location: drivers/scsi/scsi.c:670
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8182e270-ffffffff8182e317: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f2b0)
Location: drivers/scsi/scsi.c:670
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8183f2b0-ffffffff8183f357: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822430)
Location: drivers/scsi/scsi.c:683
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81822430-ffffffff818224da: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818acd70)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff818acd70-ffffffff818ace1a: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7ae0)
Location: drivers/scsi/scsi.c:713
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff819f7ae0-ffffffff819f7b94: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b753b0)
Location: drivers/scsi/scsi.c:713
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81b753b0-ffffffff81b75464: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc8ce0)
Location: drivers/scsi/scsi.c:869
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81bc8ce0-ffffffff81bc8d94: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1dbd0)
Location: drivers/scsi/scsi.c:898
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81c1dbd0-ffffffff81c1dc84: scsi_device_lookup_by_target (STB_GLOBAL)
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
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096df90)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffff80001096df90-ffff80001096e0b0: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a43b00)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
c0a43b00-c0a43bc8: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a27770)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
c000000000a27770-c000000000a278ac: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d88d6)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffe0005d88d6-ffffffe0005d897a: scsi_device_lookup_by_target (STB_GLOBAL)
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
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720750)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81720750-ffffffff817207fa: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f9b80)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816f9b80-ffffffff816f9c2a: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f520)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8175f520-ffffffff8175f5ca: scsi_device_lookup_by_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct scsi_device *scsi_device_lookup_by_target(struct scsi_target *starget, u64 lun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177ab80)
Location: drivers/scsi/scsi.c:680
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8177ab80-ffffffff8177ac2a: scsi_device_lookup_by_target (STB_GLOBAL)
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
