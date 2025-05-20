# Function: <code>ata_eh_request_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8163020a)
Location: drivers/ata/libata-eh.c:1651
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8166135a)
Location: drivers/ata/libata-eh.c:1651
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81676b1d)
Location: drivers/ata/libata-eh.c:1588
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff816e017c)
Location: drivers/ata/libata-eh.c:1586
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8171c8ee)
Location: drivers/ata/libata-eh.c:1541
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8173ee18)
Location: drivers/ata/libata-eh.c:1537
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8177abc8)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179e70c)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81863267)
Location: drivers/ata/libata-eh.c:1396
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81872077)
Location: drivers/ata/libata-eh.c:1396
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81854710)
Location: drivers/ata/libata-eh.c:1396
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e2b90)
Location: drivers/ata/libata-eh.c:1404
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ata_eh_request_sense(struct ata_queued_cmd *qc, struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:1404
Inline: False
```
**Symbols:**

```
ffffffff81a32180-ffffffff81a322b1: ata_eh_request_sense (STB_LOCAL)
ffffffff81ed862d-ffffffff81ed8699: ata_eh_request_sense.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_eh_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb66a0)
Location: drivers/ata/libata-eh.c:1402
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
```
**Symbols:**

```
ffffffff81bb66a0-ffffffff81bb688b: ata_eh_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ata_eh_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0dd10)
Location: drivers/ata/libata-eh.c:1408
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
```
**Symbols:**

```
ffffffff81c0dd10-ffffffff81c0deed: ata_eh_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ata_eh_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c62f50)
Location: drivers/ata/libata-eh.c:1415
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
```
**Symbols:**

```
ffffffff81c62f50-ffffffff81c6312d: ata_eh_request_sense (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109aa028)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a798dc)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a70bf8)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000608056)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817637fc)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8174365c)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179358c)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817ad3e5)
Location: drivers/ata/libata-eh.c:1520
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct scsi_cmnd *cmd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
