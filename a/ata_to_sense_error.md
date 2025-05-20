# Function: <code>ata_to_sense_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815d0530)
Location: drivers/ata/libata-scsi.c:844
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff815d0530-ffffffff815d0669: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81629230)
Location: drivers/ata/libata-scsi.c:885
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81629230-ffffffff8162935e: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81659f40)
Location: drivers/ata/libata-scsi.c:964
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81659f40-ffffffff8165a06e: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8166e2b0)
Location: drivers/ata/libata-scsi.c:953
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff8166e2b0-ffffffff8166e3e6: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816d79d0)
Location: drivers/ata/libata-scsi.c:954
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff816d79d0-ffffffff816d7b06: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:957
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81714380-ffffffff8171448d: ata_to_sense_error (STB_LOCAL)
ffffffff81719c46-ffffffff81719c72: ata_to_sense_error.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:952
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81736940-ffffffff81736a4d: ata_to_sense_error (STB_LOCAL)
ffffffff8173c546-ffffffff8173c572: ata_to_sense_error.cold.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff817724d0-ffffffff817725a2: ata_to_sense_error (STB_LOCAL)
ffffffff81778006-ffffffff81778032: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81796430-ffffffff81796502: ata_to_sense_error (STB_LOCAL)
ffffffff8179bf46-ffffffff8179bf72: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:719
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff8185a4d0-ffffffff8185a5a2: ata_to_sense_error (STB_LOCAL)
ffffffff8185fcac-ffffffff8185fcd5: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:719
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff818695d0-ffffffff818696a2: ata_to_sense_error (STB_LOCAL)
ffffffff81c18067-ffffffff81c18090: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:717
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff8184c000-ffffffff8184c0cf: ata_to_sense_error (STB_LOCAL)
ffffffff81c09e5f-ffffffff81c09e85: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:723
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff818d9460-ffffffff818d985e: ata_to_sense_error (STB_LOCAL)
ffffffff81d0e582-ffffffff81d0e5ac: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:751
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81a2a310-ffffffff81a2a714: ata_to_sense_error (STB_LOCAL)
ffffffff81ed73c8-ffffffff81ed73ef: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bacfc0)
Location: drivers/ata/libata-scsi.c:767
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81bacfc0-ffffffff81bad41e: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c04250)
Location: drivers/ata/libata-scsi.c:770
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81c04250-ffffffff81c046ae: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5a7a0)
Location: drivers/ata/libata-scsi.c:728
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81c5a7a0-ffffffff81c5aad4: ata_to_sense_error.isra.0 (STB_LOCAL)
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
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffff8000109a0340)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffff8000109a0340-ffff8000109a0480: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a70750)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
c0a70750-c0a7088c: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a649f0)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
c000000000a649f0-c000000000a64b60: ata_to_sense_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe0006001fe)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffe0006001fe-ffffffe000600326: ata_to_sense_error (STB_LOCAL)
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
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff8175b540-ffffffff8175b612: ata_to_sense_error (STB_LOCAL)
ffffffff81761036-ffffffff81761062: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff8173b3e0-ffffffff8173b4b2: ata_to_sense_error (STB_LOCAL)
ffffffff81740e96-ffffffff81740ec2: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff8178b2b0-ffffffff8178b382: ata_to_sense_error (STB_LOCAL)
ffffffff81790dc6-ffffffff81790df2: ata_to_sense_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ata_to_sense_error(unsigned int id, u8 drv_stat, u8 drv_err, u8 *sk, u8 *asc, u8 *ascq, int verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:937
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff817a5100-ffffffff817a51d2: ata_to_sense_error (STB_LOCAL)
ffffffff817aac06-ffffffff817aac32: ata_to_sense_error.cold (STB_LOCAL)
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
