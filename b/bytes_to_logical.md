# Function: <code>bytes_to_logical</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8165837a)
Location: drivers/scsi/sd.h:182
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
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
In drivers/scsi/sd.c (ffffffff816c401a)
Location: drivers/scsi/sd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81700580)
Location: drivers/scsi/sd.h:182
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81723350)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff8175e99f)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff8178293f)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
sector_t bytes_to_logical(struct scsi_device *sdev, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81841e40)
Location: drivers/scsi/sd.h:187
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff81841e40-ffffffff81841e51: bytes_to_logical (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff8185329c)
Location: drivers/scsi/sd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81836cbc)
Location: drivers/scsi/sd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff818c44a2)
Location: drivers/scsi/sd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81a10f25)
Location: drivers/scsi/sd.h:215
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81b91195)
Location: drivers/scsi/sd.h:215
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81be76c5)
Location: drivers/scsi/sd.h:215
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81c3cc35)
Location: drivers/scsi/sd.h:216
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffff800010989584)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (c0a5b6c0)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (c000000000a4972c)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffe0005ed86a)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff8173702f)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff81718ccf)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff817777bf)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
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
In drivers/scsi/sd.c (ffffffff817915df)
Location: drivers/scsi/sd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_config_write_same
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
