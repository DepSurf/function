# Function: <code>scsi_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815af710)
Location: drivers/scsi/scsi_lib.c:1746
Inline: False
```
**Symbols:**

```
ffffffff815af710-ffffffff815af776: scsi_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81607930)
Location: drivers/scsi/scsi_lib.c:1662
Inline: False
```
**Symbols:**

```
ffffffff81607930-ffffffff8160798f: scsi_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816370c0)
Location: drivers/scsi/scsi_lib.c:1672
Inline: False
```
**Symbols:**

```
ffffffff816370c0-ffffffff8163711f: scsi_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164b670)
Location: drivers/scsi/scsi_lib.c:1708
Inline: False
```
**Symbols:**

```
ffffffff8164b670-ffffffff8164b6cf: scsi_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b49a0)
Location: drivers/scsi/scsi_lib.c:1757
Inline: False
```
**Symbols:**

```
ffffffff816b49a0-ffffffff816b4a02: scsi_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f02c0)
Location: drivers/scsi/scsi_lib.c:1793
Inline: False
```
**Symbols:**

```
ffffffff816f02c0-ffffffff816f0322: scsi_done (STB_LOCAL)
```
</details>
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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a0218f)
Location: drivers/scsi/scsi_lib.c:1633
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
Direct callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81a02060-ffffffff81a0207a: scsi_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b80875)
Location: drivers/scsi/scsi_lib.c:1633
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
Direct callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81b80730-ffffffff81b8074a: scsi_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd48ff)
Location: drivers/scsi/scsi_lib.c:1638
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
Direct callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81bd47b0-ffffffff81bd47ca: scsi_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_done(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c2956f)
Location: drivers/scsi/scsi_lib.c:1635
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
Direct callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81c29420-ffffffff81c2943a: scsi_done (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
