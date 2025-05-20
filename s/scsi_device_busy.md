# Function: <code>scsi_device_busy</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182986f)
Location: include/scsi/scsi_device.h:594
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81830515)
Location: include/scsi/scsi_device.h:594
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
```
```
In drivers/scsi/sg.c (ffffffff81840325)
Location: include/scsi/scsi_device.h:594
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b5194)
Location: include/scsi/scsi_device.h:601
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bc4e5)
Location: include/scsi/scsi_device.h:601
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
```
```
In drivers/scsi/sg.c (ffffffff818ccc25)
Location: include/scsi/scsi_device.h:601
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a002a2)
Location: include/scsi/scsi_device.h:609
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a087c5)
Location: include/scsi/scsi_device.h:609
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
```
```
In drivers/scsi/sg.c (ffffffff81a1a747)
Location: include/scsi/scsi_device.h:609
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7e8a2)
Location: include/scsi/scsi_device.h:610
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b87ab5)
Location: include/scsi/scsi_device.h:610
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
```
```
In drivers/scsi/sg.c (ffffffff81b9b8d7)
Location: include/scsi/scsi_device.h:610
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd26d5)
Location: include/scsi/scsi_device.h:612
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdb8f5)
Location: include/scsi/scsi_device.h:612
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
```
```
In drivers/scsi/sg.c (ffffffff81bf1ec7)
Location: include/scsi/scsi_device.h:612
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c27380)
Location: include/scsi/scsi_device.h:633
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c30625)
Location: include/scsi/scsi_device.h:633
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
```
```
In drivers/scsi/sg.c (ffffffff81c477b7)
Location: include/scsi/scsi_device.h:633
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
