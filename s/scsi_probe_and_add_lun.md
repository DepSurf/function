# Function: <code>scsi_probe_and_add_lun</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, int *bflagsp, struct scsi_device **sdevp, int rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b1ea0)
Location: drivers/scsi/scsi_scan.c:1049
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
**Symbols:**

```
ffffffff815b1ea0-ffffffff815b2d05: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, int *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160a2e0)
Location: drivers/scsi/scsi_scan.c:1061
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff8160a2e0-ffffffff8160b175: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, int *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81639bc0)
Location: drivers/scsi/scsi_scan.c:1059
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81639bc0-ffffffff8163aa65: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, int *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164e740)
Location: drivers/scsi/scsi_scan.c:1046
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8164e740-ffffffff8164f502: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b79e0)
Location: drivers/scsi/scsi_scan.c:1051
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff816b79e0-ffffffff816b87bb: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f4000)
Location: drivers/scsi/scsi_scan.c:1051
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff816f4000-ffffffff816f4e45: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81716650)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81716650-ffffffff8171748c: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81752700-ffffffff81752f4d: scsi_probe_and_add_lun (STB_LOCAL)
ffffffff81753f45-ffffffff81753f71: scsi_probe_and_add_lun.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81776980-ffffffff817771cd: scsi_probe_and_add_lun (STB_LOCAL)
ffffffff817781c5-ffffffff817781f1: scsi_probe_and_add_lun.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81839c70)
Location: drivers/scsi/scsi_scan.c:1042
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81839c70-ffffffff8183a0e0: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8184a630)
Location: drivers/scsi/scsi_scan.c:1042
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff8184a630-ffffffff8184aaa0: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8182d9d0)
Location: drivers/scsi/scsi_scan.c:1062
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff8182d9d0-ffffffff8182de07: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff818b97a0)
Location: drivers/scsi/scsi_scan.c:1071
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff818b97a0-ffffffff818b9bd7: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81a050f0)
Location: drivers/scsi/scsi_scan.c:1147
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81a050f0-ffffffff81a0554b: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b83de0)
Location: drivers/scsi/scsi_scan.c:1147
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81b83de0-ffffffff81b84231: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd7b40)
Location: drivers/scsi/scsi_scan.c:1154
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81bd7b40-ffffffff81bd7f8b: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2c7e0)
Location: drivers/scsi/scsi_scan.c:1154
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81c2c7e0-ffffffff81c2cc5a: scsi_probe_and_add_lun (STB_LOCAL)
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
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097ac80)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffff80001097ac80-ffff80001097b50c: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4ee0c)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
c0a4ee0c-c0a4f2dc: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a35b60)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
c000000000a35b60-c000000000a3671c: scsi_probe_and_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e1df0)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffe0005e1df0-ffffffe0005e257c: scsi_probe_and_add_lun (STB_LOCAL)
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
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff8172b070-ffffffff8172b8bd: scsi_probe_and_add_lun (STB_LOCAL)
ffffffff8172c8b5-ffffffff8172c8e1: scsi_probe_and_add_lun.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81704490-ffffffff81704cdd: scsi_probe_and_add_lun (STB_LOCAL)
ffffffff81705cd5-ffffffff81705d01: scsi_probe_and_add_lun.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81769e40-ffffffff8176a68d: scsi_probe_and_add_lun (STB_LOCAL)
ffffffff8176b685-ffffffff8176b6b1: scsi_probe_and_add_lun.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_probe_and_add_lun(struct scsi_target *starget, u64 lun, blist_flags_t *bflagsp, struct scsi_device **sdevp, enum scsi_scan_mode rescan, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:1043
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
**Symbols:**

```
ffffffff81785590-ffffffff81785ddf: scsi_probe_and_add_lun (STB_LOCAL)
ffffffff81786dc5-ffffffff81786df1: scsi_probe_and_add_lun.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int *bflagsp</code> ➡️ <code>blist_flags_t *bflagsp</code>
</li>
</ul>
</details>
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
