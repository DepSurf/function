# Function: <code>scsi_device_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ade90)
Location: drivers/scsi/scsi_lib.c:2568
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff815ade90-ffffffff815adfd1: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81605d60)
Location: drivers/scsi/scsi_lib.c:2441
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81605d60-ffffffff81605ea1: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81635320)
Location: drivers/scsi/scsi_lib.c:2482
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81635320-ffffffff81635461: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164a4e0)
Location: drivers/scsi/scsi_lib.c:2554
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff8164a4e0-ffffffff8164a61a: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b3760)
Location: drivers/scsi/scsi_lib.c:2632
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff816b3760-ffffffff816b38a4: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ef840)
Location: drivers/scsi/scsi_lib.c:2648
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff816ef840-ffffffff816ef978: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81712fb0)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81712fb0-ffffffff8171311c: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174e890)
Location: drivers/scsi/scsi_lib.c:2192
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff8174e890-ffffffff8174e9ee: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772a40)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81772a40-ffffffff81772b9e: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834f80)
Location: drivers/scsi/scsi_lib.c:2220
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81834f80-ffffffff81835100: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818458c0)
Location: drivers/scsi/scsi_lib.c:2228
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff818458c0-ffffffff81845a40: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828b60)
Location: drivers/scsi/scsi_lib.c:2245
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81828b60-ffffffff81828cca: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b4540)
Location: drivers/scsi/scsi_lib.c:2238
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff818b4540-ffffffff818b46aa: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819ff580)
Location: drivers/scsi/scsi_lib.c:2304
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff819ff580-ffffffff819ff6ed: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7db60)
Location: drivers/scsi/scsi_lib.c:2309
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81b7db60-ffffffff81b7dccd: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd1900)
Location: drivers/scsi/scsi_lib.c:2325
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81bd1900-ffffffff81bd1a49: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c26570)
Location: drivers/scsi/scsi_lib.c:2322
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81c26570-ffffffff81c266b9: scsi_device_set_state (STB_GLOBAL)
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
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010975f58)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffff800010975f58-ffff8000109760f4: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4a8b0)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
c0a4a8b0-c0a4aa34: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a304f0)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
c000000000a304f0-c000000000a306c0: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005de6b8)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffe0005de6b8-ffffffe0005de7d2: scsi_device_set_state (STB_GLOBAL)
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
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81727130)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81727130-ffffffff8172728e: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81700560)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81700560-ffffffff817006be: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81765f00)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff81765f00-ffffffff8176605e: scsi_device_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_device_set_state(struct scsi_device *sdev, enum scsi_device_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817815b0)
Location: drivers/scsi/scsi_lib.c:2239
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_offline_dev
```
**Symbols:**

```
ffffffff817815b0-ffffffff8178170e: scsi_device_set_state (STB_GLOBAL)
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
