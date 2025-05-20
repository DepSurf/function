# Function: <code>ata_scsi_qc_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815d24c0)
Location: drivers/ata/libata-scsi.c:1768
Inline: False
```
**Symbols:**

```
ffffffff815d24c0-ffffffff815d2818: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8162bba0)
Location: drivers/ata/libata-scsi.c:1856
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8162bba0-ffffffff8162bfde: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8165ccf0)
Location: drivers/ata/libata-scsi.c:1937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8165ccf0-ffffffff8165d12e: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816719f0)
Location: drivers/ata/libata-scsi.c:1928
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff816719f0-ffffffff81671e3a: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816db030)
Location: drivers/ata/libata-scsi.c:1929
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff816db030-ffffffff816db47c: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1932
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81717520-ffffffff817177b4: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81719c72-ffffffff81719de2: ata_scsi_qc_complete.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1927
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81739b70-ffffffff81739e04: ata_scsi_qc_complete (STB_LOCAL)
ffffffff8173c572-ffffffff8173c6e2: ata_scsi_qc_complete.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81775b80-ffffffff81775e14: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81778098-ffffffff81778202: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81799af0-ffffffff81799d84: ata_scsi_qc_complete (STB_LOCAL)
ffffffff8179bf72-ffffffff8179c0dc: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1641
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8185c210-ffffffff8185c2c2: ata_scsi_qc_complete (STB_LOCAL)
ffffffff8185fe45-ffffffff8185fe65: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1641
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8186b300-ffffffff8186b3b2: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81c18200-ffffffff81c18220: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1637
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8184dc10-ffffffff8184dcc2: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81c09ff5-ffffffff81c0a015: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1639
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff818db280-ffffffff818db332: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81d0e73a-ffffffff81d0e75a: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1639
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81a2e250-ffffffff81a2e322: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81ed77d2-ffffffff81ed77ed: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81baf480)
Location: drivers/ata/libata-scsi.c:1652
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81baf480-ffffffff81baf569: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c06190)
Location: drivers/ata/libata-scsi.c:1676
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81c06190-ffffffff81c06253: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5af60)
Location: drivers/ata/libata-scsi.c:1628
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81c5af60-ffffffff81c5b001: ata_scsi_qc_complete (STB_LOCAL)
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
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffff8000109a1428)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffff8000109a1428-ffff8000109a17d4: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a70ef8)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
c0a70ef8-c0a712f4: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a69220)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
c000000000a69220-c000000000a69714: ata_scsi_qc_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe0006028a2)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffe0006028a2-ffffffe000602c42: ata_scsi_qc_complete (STB_LOCAL)
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
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8175ebe0-ffffffff8175ee74: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81761062-ffffffff817611cc: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8173ea80-ffffffff8173ed14: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81740ec2-ffffffff8174102c: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8178e970-ffffffff8178ec04: ata_scsi_qc_complete (STB_LOCAL)
ffffffff81790df2-ffffffff81790f5c: ata_scsi_qc_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ata_scsi_qc_complete(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:1931
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff817a8aa0-ffffffff817a8d34: ata_scsi_qc_complete (STB_LOCAL)
ffffffff817aac32-ffffffff817aad9c: ata_scsi_qc_complete.cold (STB_LOCAL)
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
