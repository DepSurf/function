# Function: <code>scsi_check_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815aa050)
Location: drivers/scsi/scsi_error.c:455
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
```
**Symbols:**

```
ffffffff815aa050-ffffffff815aa468: scsi_check_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81601fc0)
Location: drivers/scsi/scsi_error.c:455
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81601fc0-ffffffff816023c4: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816316b0)
Location: drivers/scsi/scsi_error.c:455
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816316b0-ffffffff81631ab4: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816461c0)
Location: drivers/scsi/scsi_error.c:440
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816461c0-ffffffff8164663e: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816af1a0)
Location: drivers/scsi/scsi_error.c:461
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816af1a0-ffffffff816af677: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816eb550)
Location: drivers/scsi/scsi_error.c:483
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816eb550-ffffffff816eba1e: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8170eff0)
Location: drivers/scsi/scsi_error.c:480
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8170eff0-ffffffff8170f50c: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174a780)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8174a780-ffffffff8174aca3: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8176e8f0)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8176e8f0-ffffffff8176ee13: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81831150)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81831150-ffffffff81831470: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81841d90)
Location: drivers/scsi/scsi_error.c:489
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81841d90-ffffffff8184207b: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum scsi_disposition scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81824f90)
Location: drivers/scsi/scsi_error.c:501
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81824f90-ffffffff8182527b: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum scsi_disposition scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818b0810)
Location: drivers/scsi/scsi_error.c:526
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff818b0810-ffffffff818b0afb: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum scsi_disposition scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff819fb940)
Location: drivers/scsi/scsi_error.c:530
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff819fb940-ffffffff819fbbf8: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum scsi_disposition scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b79a80)
Location: drivers/scsi/scsi_error.c:537
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
```
**Symbols:**

```
ffffffff81b79a80-ffffffff81b79d38: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum scsi_disposition scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcd710)
Location: drivers/scsi/scsi_error.c:537
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81bcd710-ffffffff81bcda41: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum scsi_disposition scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c22340)
Location: drivers/scsi/scsi_error.c:539
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81c22340-ffffffff81c2266c: scsi_check_sense (STB_GLOBAL)
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
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff8000109715d8)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffff8000109715d8-ffff800010971b68: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a4641c)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
c0a4641c-c0a4696c: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2af70)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
c000000000a2af70-c000000000a2b5d4: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005dadca)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffe0005dadca-ffffffe0005db248: scsi_check_sense (STB_GLOBAL)
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
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81722fe0)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81722fe0-ffffffff81723503: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816fc410)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816fc410-ffffffff816fc933: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81761db0)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81761db0-ffffffff817622d3: scsi_check_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_check_sense(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8177d410)
Location: drivers/scsi/scsi_error.c:481
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8177d410-ffffffff8177d933: scsi_check_sense (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum scsi_disposition</code>
</li>
</ul>
</details>
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
