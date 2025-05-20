# Function: <code>__scsi_remove_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff815b5b80)
Location: drivers/scsi/scsi_sysfs.c:1101
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff815b5b80-ffffffff815b5c58: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e290)
Location: drivers/scsi/scsi_sysfs.c:1276
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff8160e290-ffffffff8160e360: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8163db30)
Location: drivers/scsi/scsi_sysfs.c:1272
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff8163db30-ffffffff8163dc00: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81652680)
Location: drivers/scsi/scsi_sysfs.c:1274
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff81652680-ffffffff816527a4: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff816bba70)
Location: drivers/scsi/scsi_sysfs.c:1319
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff816bba70-ffffffff816bbb9b: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff816f7ec0)
Location: drivers/scsi/scsi_sysfs.c:1339
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff816f7ec0-ffffffff816f800f: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8171a7c0)
Location: drivers/scsi/scsi_sysfs.c:1345
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff8171a7c0-ffffffff8171a90f: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81755e90)
Location: drivers/scsi/scsi_sysfs.c:1357
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff81755e90-ffffffff81755fdb: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8177a110)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff8177a110-ffffffff8177a25b: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d170)
Location: drivers/scsi/scsi_sysfs.c:1386
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff8183d170-ffffffff8183d2be: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8184d970)
Location: drivers/scsi/scsi_sysfs.c:1397
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff8184d970-ffffffff8184dabe: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81830e10)
Location: drivers/scsi/scsi_sysfs.c:1403
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff81830e10-ffffffff81830f5e: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff818bce50)
Location: drivers/scsi/scsi_sysfs.c:1428
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_free_host_dev
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff818bce50-ffffffff818bcfa9: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81a09000)
Location: drivers/scsi/scsi_sysfs.c:1426
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff81a09000-ffffffff81a09154: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81b88400)
Location: drivers/scsi/scsi_sysfs.c:1420
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff81b88400-ffffffff81b88594: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc2e0)
Location: drivers/scsi/scsi_sysfs.c:1450
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff81bdc2e0-ffffffff81bdc47b: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81c31010)
Location: drivers/scsi/scsi_sysfs.c:1450
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
```
**Symbols:**

```
ffffffff81c31010-ffffffff81c311ab: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffff80001097f800)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffff80001097f800-ffff80001097f938: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (c0a525f4)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
c0a525f4-c0a52734: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (c000000000a3b330)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_free_host_dev
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
c000000000a3b330-c000000000a3b520: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e5a34)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffe0005e5a34-ffffffe0005e5b72: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8172e800)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff8172e800-ffffffff8172e94b: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81707c20)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff81707c20-ffffffff81707d6b: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8176d5d0)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff8176d5d0-ffffffff8176d71b: __scsi_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __scsi_remove_device(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff81788d70)
Location: drivers/scsi/scsi_sysfs.c:1366
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_remove_device
```
**Symbols:**

```
ffffffff81788d70-ffffffff81788ebb: __scsi_remove_device (STB_GLOBAL)
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
