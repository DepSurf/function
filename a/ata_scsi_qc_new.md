# Function: <code>ata_scsi_qc_new</code>

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
In drivers/ata/libata-scsi.c (ffffffff815d1131)
Location: drivers/ata/libata-scsi.c:753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff8162a531)
Location: drivers/ata/libata-scsi.c:794
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff8165b7b1)
Location: drivers/ata/libata-scsi.c:873
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff81670295)
Location: drivers/ata/libata-scsi.c:862
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff816d9895)
Location: drivers/ata/libata-scsi.c:863
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff81715d45)
Location: drivers/ata/libata-scsi.c:863
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff81738385)
Location: drivers/ata/libata-scsi.c:858
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff817743d1)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff81798341)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff8185ac11)
Location: drivers/ata/libata-scsi.c:625
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff81869d11)
Location: drivers/ata/libata-scsi.c:625
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff8184c5d1)
Location: drivers/ata/libata-scsi.c:623
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff818d9c37)
Location: drivers/ata/libata-scsi.c:629
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ata_queued_cmd *ata_scsi_qc_new(struct ata_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2b300)
Location: drivers/ata/libata-scsi.c:638
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff81a2b300-ffffffff81a2b4bf: ata_scsi_qc_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ata_queued_cmd *ata_scsi_qc_new(struct ata_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bae390)
Location: drivers/ata/libata-scsi.c:654
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff81bae390-ffffffff81bae54f: ata_scsi_qc_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ata_queued_cmd *ata_scsi_qc_new(struct ata_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c05b40)
Location: drivers/ata/libata-scsi.c:657
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff81c05b40-ffffffff81c05d35: ata_scsi_qc_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ata_queued_cmd *ata_scsi_qc_new(struct ata_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c59b70)
Location: drivers/ata/libata-scsi.c:657
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff81c59b70-ffffffff81c59d65: ata_scsi_qc_new (STB_LOCAL)
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
In drivers/ata/libata-scsi.c (ffff8000109a096c)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (c0a73240)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (c000000000a67a30)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffe000601b58)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff8175d451)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff8173d2f1)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff8178d1c1)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/ata/libata-scsi.c (ffffffff817a7011)
Location: drivers/ata/libata-scsi.c:843
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
