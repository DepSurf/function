# Function: <code>scsi_stop_queue</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00604)
Location: drivers/scsi/scsi_lib.c:2716
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_stop_queue(struct scsi_device *sdev, bool nowait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7e650)
Location: drivers/scsi/scsi_lib.c:2721
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81b7e650-ffffffff81b7e6be: scsi_stop_queue (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff81bd293a)
Location: drivers/scsi/scsi_lib.c:2737
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
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
In drivers/scsi/scsi_lib.c (ffffffff81c275aa)
Location: drivers/scsi/scsi_lib.c:2734
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
