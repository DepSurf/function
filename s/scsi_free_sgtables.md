# Function: <code>scsi_free_sgtables</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8183810e)
Location: drivers/scsi/scsi_lib.c:534
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81848a50)
Location: drivers/scsi/scsi_lib.c:519
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81845440-ffffffff81845493: scsi_free_sgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182bd68)
Location: drivers/scsi/scsi_lib.c:486
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff818285c0-ffffffff81828613: scsi_free_sgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b792a)
Location: drivers/scsi/scsi_lib.c:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff818b3f00-ffffffff818b3f53: scsi_free_sgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a02e9e)
Location: drivers/scsi/scsi_lib.c:492
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff819feef0-ffffffff819fef5b: scsi_free_sgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b819f0)
Location: drivers/scsi/scsi_lib.c:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81b7d4d0-ffffffff81b7d53b: scsi_free_sgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd5735)
Location: drivers/scsi/scsi_lib.c:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81bd1260-ffffffff81bd12cb: scsi_free_sgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c2a389)
Location: drivers/scsi/scsi_lib.c:485
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
**Symbols:**

```
ffffffff81c25ed0-ffffffff81c25f3b: scsi_free_sgtables (STB_GLOBAL)
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
