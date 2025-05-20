# Function: <code>scsi_alloc_sdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b1b10)
Location: drivers/scsi/scsi_scan.c:210
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
```
**Symbols:**

```
ffffffff815b1b10-ffffffff815b1dff: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81609f10)
Location: drivers/scsi/scsi_scan.c:214
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81609f10-ffffffff8160a20a: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816397f0)
Location: drivers/scsi/scsi_scan.c:214
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816397f0-ffffffff81639aea: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164e370)
Location: drivers/scsi/scsi_scan.c:214
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8164e370-ffffffff8164e66d: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b7610)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816b7610-ffffffff816b7910: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f3d10)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff816f3d10-ffffffff816f3fff: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817162f0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff817162f0-ffffffff8171657f: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81752430)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81752430-ffffffff817526f4: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817766b0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff817766b0-ffffffff81776974: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff818399c0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff818399c0-ffffffff81839c6d: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8184a380)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8184a380-ffffffff8184a62d: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8182d3d0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8182d3d0-ffffffff8182d71c: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff818b9420-ffffffff818b979d: scsi_alloc_sdev (STB_LOCAL)
ffffffff81d0c748-ffffffff81d0c777: scsi_alloc_sdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81a04b00)
Location: drivers/scsi/scsi_scan.c:278
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81a04b00-ffffffff81a04dd3: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b83770)
Location: drivers/scsi/scsi_scan.c:278
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81b83770-ffffffff81b83a7d: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd74d0)
Location: drivers/scsi/scsi_scan.c:278
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81bd74d0-ffffffff81bd77e0: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2c170)
Location: drivers/scsi/scsi_scan.c:278
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81c2c170-ffffffff81c2c47d: scsi_alloc_sdev (STB_LOCAL)
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
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097aa38)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffff80001097aa38-ffff80001097ac7c: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4eb88)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
c0a4eb88-c0a4ee0c: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a35850)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
c000000000a35850-c000000000a35b60: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e1bca)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffe0005e1bca-ffffffe0005e1df0: scsi_alloc_sdev (STB_LOCAL)
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
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8172ada0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8172ada0-ffffffff8172b064: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817041c0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff817041c0-ffffffff81704484: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81769b70)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81769b70-ffffffff81769e34: scsi_alloc_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct scsi_device *scsi_alloc_sdev(struct scsi_target *starget, u64 lun, void *hostdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817852c0)
Location: drivers/scsi/scsi_scan.c:215
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff817852c0-ffffffff81785584: scsi_alloc_sdev (STB_LOCAL)
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
