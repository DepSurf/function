# Function: <code>ata_eh_read_log_10h</code>

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
In drivers/ata/libata-eh.c (ffffffff815d6480)
Location: drivers/ata/libata-eh.c:1568
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff8162fee0)
Location: drivers/ata/libata-eh.c:1568
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff81661030)
Location: drivers/ata/libata-eh.c:1568
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff81675ff0)
Location: drivers/ata/libata-eh.c:1505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff816df640)
Location: drivers/ata/libata-eh.c:1503
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff8171be6c)
Location: drivers/ata/libata-eh.c:1458
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff8173e73c)
Location: drivers/ata/libata-eh.c:1454
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff8177a5fe)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff8179e13e)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_eh_read_log_10h(struct ata_device *dev, int *tag, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81867cc0)
Location: drivers/ata/libata-sata.c:1369
Inline: False
Direct callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81867cc0-ffffffff81867e3d: ata_eh_read_log_10h (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ata_eh_read_log_10h(struct ata_device *dev, int *tag, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81876ad0)
Location: drivers/ata/libata-sata.c:1369
Inline: False
Direct callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81876ad0-ffffffff81876c4d: ata_eh_read_log_10h (STB_LOCAL)
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
In drivers/ata/libata-sata.c (ffffffff818593be)
Location: drivers/ata/libata-sata.c:1369
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-sata.c (ffffffff818e7f59)
Location: drivers/ata/libata-sata.c:1381
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81a39a39)
Location: drivers/ata/libata-sata.c:1360
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81bbebec)
Location: drivers/ata/libata-sata.c:1360
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c1687c)
Location: drivers/ata/libata-sata.c:1384
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c6b9bc)
Location: drivers/ata/libata-sata.c:1302
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffff8000109a9b48)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (c0a793a0)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (c000000000a70660)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffe000607676)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff8176322e)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff8174308e)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff81792fbe)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
In drivers/ata/libata-eh.c (ffffffff817acdfe)
Location: drivers/ata/libata-eh.c:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
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
</ul>
