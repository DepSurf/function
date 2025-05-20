# Function: <code>atapi_request_sense</code>

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
In drivers/ata/libata-scsi.c (ffffffff815d2ef4)
Location: drivers/ata/libata-scsi.c:2606
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8162c8f4)
Location: drivers/ata/libata-scsi.c:2746
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8165d744)
Location: drivers/ata/libata-scsi.c:2827
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81670a8e)
Location: drivers/ata/libata-scsi.c:2806
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff816da0a0)
Location: drivers/ata/libata-scsi.c:2807
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81716580)
Location: drivers/ata/libata-scsi.c:2810
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81738bc0)
Location: drivers/ata/libata-scsi.c:2805
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81774bfa)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff81798b6a)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void atapi_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185a2e0)
Location: drivers/ata/libata-scsi.c:2521
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff8185a2e0-ffffffff8185a4c4: atapi_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void atapi_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818693e0)
Location: drivers/ata/libata-scsi.c:2521
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff818693e0-ffffffff818695c4: atapi_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void atapi_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8184be10)
Location: drivers/ata/libata-scsi.c:2517
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff8184be10-ffffffff8184bff4: atapi_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void atapi_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818d9270)
Location: drivers/ata/libata-scsi.c:2477
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff818d9270-ffffffff818d9454: atapi_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void atapi_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2a960)
Location: drivers/ata/libata-scsi.c:2488
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff81a2a960-ffffffff81a2ab2e: atapi_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void atapi_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bad580)
Location: drivers/ata/libata-scsi.c:2501
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff81bad580-ffffffff81bad74e: atapi_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void atapi_request_sense(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c04ac0)
Location: drivers/ata/libata-scsi.c:2631
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff81c04ac0-ffffffff81c04c8c: atapi_request_sense (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/ata/libata-scsi.c (ffff8000109a0e60)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (c0a70d10)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (c000000000a65120)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffe0006006fe)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8175dc5a)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8173dafa)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff8178d9ea)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
In drivers/ata/libata-scsi.c (ffffffff817a783a)
Location: drivers/ata/libata-scsi.c:2809
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
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
</ul>
