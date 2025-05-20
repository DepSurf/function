# Function: <code>ata_gen_ata_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815d254f)
Location: drivers/ata/libata-scsi.c:1049
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8162bd8d)
Location: drivers/ata/libata-scsi.c:1115
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8165cedd)
Location: drivers/ata/libata-scsi.c:1194
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81671ad6)
Location: drivers/ata/libata-scsi.c:1182
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff816db118)
Location: drivers/ata/libata-scsi.c:1183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81717589)
Location: drivers/ata/libata-scsi.c:1186
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81739bd9)
Location: drivers/ata/libata-scsi.c:1181
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81775be8)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81799b58)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185c030)
Location: drivers/ata/libata-scsi.c:948
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff8185c030-ffffffff8185c20f: ata_gen_ata_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8186b120)
Location: drivers/ata/libata-scsi.c:948
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff8186b120-ffffffff8186b2ff: ata_gen_ata_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8184da50)
Location: drivers/ata/libata-scsi.c:945
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff8184da50-ffffffff8184dc0c: ata_gen_ata_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818db0c0)
Location: drivers/ata/libata-scsi.c:949
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff818db0c0-ffffffff818db271: ata_gen_ata_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff81a2e0c0-ffffffff81a2e244: ata_gen_ata_sense (STB_LOCAL)
ffffffff81ed7795-ffffffff81ed77d2: ata_gen_ata_sense.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81baf290)
Location: drivers/ata/libata-scsi.c:993
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff81baf290-ffffffff81baf466: ata_gen_ata_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c048e0)
Location: drivers/ata/libata-scsi.c:996
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff81c048e0-ffffffff81c04aa3: ata_gen_ata_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_gen_ata_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5aaf0)
Location: drivers/ata/libata-scsi.c:947
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff81c5aaf0-ffffffff81c5ac8b: ata_gen_ata_sense (STB_LOCAL)
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
In drivers/ata/libata-scsi.c (ffff8000109a150c)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (c0a70fec)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (c000000000a692a0)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffe0006028f4)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8175ec48)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8173eae8)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8178e9d8)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff817a8b08)
Location: drivers/ata/libata-scsi.c:1166
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
