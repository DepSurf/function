# Function: <code>ata_eh_unload</code>

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
In drivers/ata/libata-eh.c (ffffffff815da095)
Location: drivers/ata/libata-eh.c:553
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff81633c35)
Location: drivers/ata/libata-eh.c:553
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff81664d85)
Location: drivers/ata/libata-eh.c:553
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff816797ee)
Location: drivers/ata/libata-eh.c:554
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff816e2e5c)
Location: drivers/ata/libata-eh.c:554
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff8171f689)
Location: drivers/ata/libata-eh.c:503
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff81741f79)
Location: drivers/ata/libata-eh.c:503
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff8177dac2)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff817a18d2)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_eh_unload(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861b10)
Location: drivers/ata/libata-eh.c:485
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81861b10-ffffffff81861c0e: ata_eh_unload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_eh_unload(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870920)
Location: drivers/ata/libata-eh.c:485
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81870920-ffffffff81870a1e: ata_eh_unload (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffffffff81856c71)
Location: drivers/ata/libata-eh.c:485
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff818e54ed)
Location: drivers/ata/libata-eh.c:493
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff81a367ed)
Location: drivers/ata/libata-eh.c:493
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff81bbb38f)
Location: drivers/ata/libata-eh.c:495
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff81c12bca)
Location: drivers/ata/libata-eh.c:495
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_eh_unload(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c62740)
Location: drivers/ata/libata-eh.c:509
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81c62740-ffffffff81c62921: ata_eh_unload (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffff8000109ad17c)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (c0a7c9c0)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (c000000000a7436c)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffe00060a602)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff8176698f)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff817467ef)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff81796752)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
In drivers/ata/libata-eh.c (ffffffff817b05c2)
Location: drivers/ata/libata-eh.c:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
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
