# Function: <code>scsi_is_host_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815a7d70)
Location: drivers/scsi/hosts.c:611
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff815a7d70-ffffffff815a7d88: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815ffbf0)
Location: drivers/scsi/hosts.c:624
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff815ffbf0-ffffffff815ffc08: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8162f250)
Location: drivers/scsi/hosts.c:628
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff8162f250-ffffffff8162f268: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81644030)
Location: drivers/scsi/hosts.c:616
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff81644030-ffffffff81644048: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816acfd0)
Location: drivers/scsi/hosts.c:611
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff816acfd0-ffffffff816acfe8: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816e959d)
Location: drivers/scsi/hosts.c:587
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff816e94e0-ffffffff816e94f8: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8170d0b9)
Location: drivers/scsi/hosts.c:584
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff8170d000-ffffffff8170d018: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81748bdc)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff817486f0-ffffffff81748708: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8176cd2c)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff8176c840-ffffffff8176c858: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182eddc)
Location: drivers/scsi/hosts.c:605
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff8182ecb0-ffffffff8182ecc8: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8183fdfc)
Location: drivers/scsi/hosts.c:608
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff8183fcf0-ffffffff8183fd08: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182305c)
Location: drivers/scsi/hosts.c:612
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff81822f70-ffffffff81822f88: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818ad97c)
Location: drivers/scsi/hosts.c:614
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff818ad890-ffffffff818ad8a8: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff819f880a)
Location: drivers/scsi/hosts.c:616
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff819f8710-ffffffff819f872e: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b7627a)
Location: drivers/scsi/hosts.c:631
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff81b760f0-ffffffff81b7610e: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bc9f0a)
Location: drivers/scsi/hosts.c:631
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff81bc9d80-ffffffff81bc9d9e: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1eb3a)
Location: drivers/scsi/hosts.c:631
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff81c1e9b0-ffffffff81c1e9ce: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffff80001096f05c)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffff80001096ef00-ffff80001096ef38: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c0a443bc)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
c0a442b8-c0a442e8: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c000000000a2894c)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
  - drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers
  - drivers/scsi/scsi_transport_srp.c:rport_dev_loss_timedout
  - drivers/scsi/scsi_transport_srp.c:rport_fast_io_fail_timedout
  - drivers/scsi/scsi_transport_srp.c:__rport_fail_io_fast
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_work
  - drivers/scsi/scsi_transport_srp.c:store_srp_rport_delete
  - drivers/scsi/scsi_transport_srp.c:srp_host_setup
```
**Symbols:**

```
c000000000a28310-c000000000a2833c: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffe0005d917a)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffe0005d9000-ffffffe0005d9030: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8172141c)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff81720f30-ffffffff81720f48: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816fa84c)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_dispatch
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_dispatch
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_dispatch
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout
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
**Symbols:**

```
ffffffff816fa360-ffffffff816fa378: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff817601ec)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff8175fd00-ffffffff8175fd18: scsi_is_host_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int scsi_is_host_device(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8177b84c)
Location: drivers/scsi/hosts.c:588
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_pm.c:scsi_bus_prepare
```
**Symbols:**

```
ffffffff8177b360-ffffffff8177b378: scsi_is_host_device (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
