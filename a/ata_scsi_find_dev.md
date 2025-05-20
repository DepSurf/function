# Function: <code>ata_scsi_find_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815d1990)
Location: drivers/ata/libata-scsi.c:2881
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff815d1990-ffffffff815d19cb: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8162ae30)
Location: drivers/ata/libata-scsi.c:3021
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff8162ae30-ffffffff8162ae68: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8165c0c0)
Location: drivers/ata/libata-scsi.c:3102
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff8165c0c0-ffffffff8165c0f8: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81671720)
Location: drivers/ata/libata-scsi.c:3081
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff81671720-ffffffff81671753: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816dad00)
Location: drivers/ata/libata-scsi.c:3082
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff816dad00-ffffffff816dad33: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817171f0)
Location: drivers/ata/libata-scsi.c:3085
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff817171f0-ffffffff81717223: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81739840)
Location: drivers/ata/libata-scsi.c:3080
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff81739840-ffffffff81739873: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81775840)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff81775840-ffffffff81775873: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817997b0)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff817997b0-ffffffff817997e3: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185e890)
Location: drivers/ata/libata-scsi.c:2796
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
```
**Symbols:**

```
ffffffff8185e890-ffffffff8185e8c8: ata_scsi_find_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8186d8b0)
Location: drivers/ata/libata-scsi.c:2796
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
```
**Symbols:**

```
ffffffff8186d8b0-ffffffff8186d8e8: ata_scsi_find_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81850e00)
Location: drivers/ata/libata-scsi.c:2792
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
```
**Symbols:**

```
ffffffff81850790-ffffffff818507c8: ata_scsi_find_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818de990)
Location: drivers/ata/libata-scsi.c:2752
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
```
**Symbols:**

```
ffffffff818ddf90-ffffffff818ddfc8: ata_scsi_find_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2ed40)
Location: drivers/ata/libata-scsi.c:2756
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
```
**Symbols:**

```
ffffffff81a2ed40-ffffffff81a2ed93: ata_scsi_find_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bb2250)
Location: drivers/ata/libata-scsi.c:2769
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
```
**Symbols:**

```
ffffffff81bb2250-ffffffff81bb22a3: ata_scsi_find_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c09780)
Location: drivers/ata/libata-scsi.c:2917
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-sata.c:ata_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
```
**Symbols:**

```
ffffffff81c09780-ffffffff81c097d3: ata_scsi_find_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5e840)
Location: drivers/ata/libata-scsi.c:2789
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-sata.c:ata_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
```
**Symbols:**

```
ffffffff81c5e840-ffffffff81c5e893: ata_scsi_find_dev (STB_GLOBAL)
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
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffff8000109a1250)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffff8000109a1250-ffff8000109a12ac: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a74108)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
c0a74108-c0a74144: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a68d40)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
c000000000a68d40-c000000000a68d94: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe0006024ba)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffe0006024ba-ffffffe000602504: ata_scsi_find_dev (STB_LOCAL)
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
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8175e8a0)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff8175e8a0-ffffffff8175e8d3: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8173e740)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff8173e740-ffffffff8173e773: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8178e630)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff8178e630-ffffffff8178e663: ata_scsi_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ata_device *ata_scsi_find_dev(struct ata_port *ap, const struct scsi_device *scsidev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817a8480)
Location: drivers/ata/libata-scsi.c:3084
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
**Symbols:**

```
ffffffff817a8480-ffffffff817a84b3: ata_scsi_find_dev (STB_LOCAL)
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
