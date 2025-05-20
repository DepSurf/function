# Function: <code>dev_to_shost</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a68e3)
Location: include/scsi/scsi_host.h:759
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
```
```
In drivers/scsi/hosts.c (ffffffff815a8373)
Location: include/scsi/scsi_host.h:759
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b1a2d)
Location: include/scsi/scsi_host.h:759
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_scan_target
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b5cee)
Location: include/scsi/scsi_host.h:759
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fecce)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81600203)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160be0a)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e3ee)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162e31e)
Location: include/scsi/scsi_host.h:764
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff8162f8e3)
Location: include/scsi/scsi_host.h:764
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163b6aa)
Location: include/scsi/scsi_host.h:764
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163dc8e)
Location: include/scsi/scsi_host.h:764
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8164370e)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81644323)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8165023a)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8165283e)
Location: include/scsi/scsi_host.h:756
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac81e)
Location: include/scsi/scsi_host.h:751
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff816ad2d1)
Location: include/scsi/scsi_host.h:751
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b943a)
Location: include/scsi/scsi_host.h:751
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816bbc2e)
Location: include/scsi/scsi_host.h:751
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8d4c)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff816e9585)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f5765)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f80ec)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c83c)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff8170d0a5)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81718085)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8171a9ec)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747f2c)
Location: include/scsi/scsi_host.h:704
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81748bc5)
Location: include/scsi/scsi_host.h:704
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff817537e5)
Location: include/scsi/scsi_host.h:704
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff817560bd)
Location: include/scsi/scsi_host.h:704
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176c07c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff8176cd15)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81777a65)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8177a35d)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e28c)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff8182edc5)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183a9c5)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d50d)
Location: include/scsi/scsi_host.h:710
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f2cc)
Location: include/scsi/scsi_host.h:717
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff8183fde5)
Location: include/scsi/scsi_host.h:717
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184b395)
Location: include/scsi/scsi_host.h:717
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184dd0d)
Location: include/scsi/scsi_host.h:717
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182244c)
Location: include/scsi/scsi_host.h:733
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81823045)
Location: include/scsi/scsi_host.h:733
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182e705)
Location: include/scsi/scsi_host.h:733
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183108d)
Location: include/scsi/scsi_host.h:733
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi.c (ffffffff818acd8c)
Location: include/scsi/scsi_host.h:734
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff818ad965)
Location: include/scsi/scsi_host.h:734
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff818ba4d5)
Location: include/scsi/scsi_host.h:734
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bd0dd)
Location: include/scsi/scsi_host.h:734
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi.c (ffffffff819f7afc)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff819f87f5)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a05f45)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a0929d)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi.c (ffffffff81b753cc)
Location: include/scsi/scsi_host.h:729
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81b76265)
Location: include/scsi/scsi_host.h:729
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b84ce5)
Location: include/scsi/scsi_host.h:729
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b8870d)
Location: include/scsi/scsi_host.h:729
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi.c (ffffffff81bc8cfc)
Location: include/scsi/scsi_host.h:735
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81bc9ef5)
Location: include/scsi/scsi_host.h:735
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd8a65)
Location: include/scsi/scsi_host.h:735
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc5ed)
Location: include/scsi/scsi_host.h:735
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi.c (ffffffff81c1dbec)
Location: include/scsi/scsi_host.h:738
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81c1eb25)
Location: include/scsi/scsi_host.h:738
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2d765)
Location: include/scsi/scsi_host.h:738
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c3131d)
Location: include/scsi/scsi_host.h:738
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096dfb4)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffff80001096f050)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffff80001097c514)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097fa5c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a43b18)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (c0a4439c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (c0a4fe40)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (c0a52854)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a2779c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (c000000000a28928)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (c000000000a37464)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a3b6c0)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/scsi_transport_srp.c (c000000000a41ef4)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
  - drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers
  - drivers/scsi/scsi_transport_srp.c:rport_dev_loss_timedout
  - drivers/scsi/scsi_transport_srp.c:rport_fast_io_fail_timedout
  - drivers/scsi/scsi_transport_srp.c:__rport_fail_io_fast
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_work
  - drivers/scsi/scsi_transport_srp.c:store_srp_rport_delete
  - drivers/scsi/scsi_transport_srp.c:srp_host_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d88f8)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffe0005d916a)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e310e)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e5c88)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8172076c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff81721405)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172c155)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172ea4d)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f9b9c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff816fa835)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81705575)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81707e6d)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff81710179)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_dispatch
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_dispatch
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout
  - drivers/scsi/scsi_transport_fc.c:fc_block_rport
  - drivers/scsi/scsi_transport_fc.c:fc_scsi_scan_rport
  - drivers/scsi/scsi_transport_fc.c:fc_timeout_deleted_rport
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_delete
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/scsi/scsi_transport_fc.c:fc_terminate_rport_io
  - drivers/scsi/scsi_transport_fc.c:store_fc_host_vport_delete
  - drivers/scsi/scsi_transport_fc.c:store_fc_host_vport_create
  - drivers/scsi/scsi_transport_fc.c:fc_reset_statistics
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_npiv_vports_inuse
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_dev_loss_tmo
  - drivers/scsi/scsi_transport_fc.c:store_fc_private_host_dev_loss_tmo
  - drivers/scsi/scsi_transport_fc.c:store_fc_private_host_issue_lip
  - drivers/scsi/scsi_transport_fc.c:store_fc_private_host_tgtid_bind_type
  - drivers/scsi/scsi_transport_fc.c:show_fc_private_host_tgtid_bind_type
  - drivers/scsi/scsi_transport_fc.c:store_fc_host_system_hostname
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_system_hostname
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_symbolic_name
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_fabric_name
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_port_state
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_port_type
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_port_id
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_active_fc4s
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_optionrom_version
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_firmware_version
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_driver_version
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_hardware_version
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_model_description
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_model
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_manufacturer
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_serial_number
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_max_npiv_vports
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_maxframe_size
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_permanent_port_name
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_port_name
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_node_name
  - drivers/scsi/scsi_transport_fc.c:show_fc_host_supported_fc4s
  - drivers/scsi/scsi_transport_fc.c:show_fc_starget_port_id
  - drivers/scsi/scsi_transport_fc.c:show_fc_starget_port_name
  - drivers/scsi/scsi_transport_fc.c:show_fc_starget_node_name
  - drivers/scsi/scsi_transport_fc.c:show_fc_rport_dev_loss_tmo
  - drivers/scsi/scsi_transport_fc.c:fc_rport_set_dev_loss_tmo
  - drivers/scsi/scsi_transport_fc.c:fc_host_remove
  - drivers/scsi/scsi_transport_fc.c:fc_host_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f53c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff817601d5)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176af25)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176d81d)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177ab9c)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
```
```
In drivers/scsi/hosts.c (ffffffff8177b835)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81786675)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81788fbd)
Location: include/scsi/scsi_host.h:716
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
</ul>

## Differences
