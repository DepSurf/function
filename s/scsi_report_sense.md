# Function: <code>scsi_report_sense</code>

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
In drivers/scsi/scsi_error.c (ffffffff815aa0b3)
Location: drivers/scsi/scsi_error.c:388
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff81602023)
Location: drivers/scsi/scsi_error.c:388
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff81631713)
Location: drivers/scsi/scsi_error.c:388
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff81646205)
Location: drivers/scsi/scsi_error.c:373
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff816af1e5)
Location: drivers/scsi/scsi_error.c:388
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff816eb596)
Location: drivers/scsi/scsi_error.c:410
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff8170f036)
Location: drivers/scsi/scsi_error.c:407
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff8174a7ca)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff8176e93a)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81830f60)
Location: drivers/scsi/scsi_error.c:408
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff81830f60-ffffffff81831149: scsi_report_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81841ba0)
Location: drivers/scsi/scsi_error.c:416
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff81841ba0-ffffffff81841d89: scsi_report_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81824da0)
Location: drivers/scsi/scsi_error.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff81824da0-ffffffff81824f89: scsi_report_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818b0620)
Location: drivers/scsi/scsi_error.c:453
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff818b0620-ffffffff818b0809: scsi_report_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff819fb6c0)
Location: drivers/scsi/scsi_error.c:452
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff819fb6c0-ffffffff819fb93e: scsi_report_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b797f0)
Location: drivers/scsi/scsi_error.c:456
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff81b797f0-ffffffff81b79a6e: scsi_report_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcd480)
Location: drivers/scsi/scsi_error.c:456
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff81bcd480-ffffffff81bcd6fe: scsi_report_sense (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_report_sense(struct scsi_device *sdev, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c220b0)
Location: drivers/scsi/scsi_error.c:458
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
**Symbols:**

```
ffffffff81c220b0-ffffffff81c2232e: scsi_report_sense (STB_LOCAL)
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
In drivers/scsi/scsi_error.c (ffff800010971628)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (c0a46468)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (c000000000a2afcc)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffe0005dae00)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff8172302a)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff816fc45a)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff81761dfa)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
In drivers/scsi/scsi_error.c (ffffffff8177d45a)
Location: drivers/scsi/scsi_error.c:408
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
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
