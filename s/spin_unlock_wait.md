# Function: <code>spin_unlock_wait</code>

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
In kernel/sched/completion.c (ffffffff810c3be1)
Location: include/linux/spinlock.h:380
Inline: True
```
```
In ipc/sem.c (ffffffff81326e0d)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In drivers/ata/libata-eh.c (ffffffff815d4bea)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
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
In kernel/sched/completion.c (ffffffff810c7862)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - kernel/sched/completion.c:completion_done
```
```
In ipc/sem.c (ffffffff8135e94d)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In drivers/ata/libata-eh.c (ffffffff8162e66f)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
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
In kernel/sched/completion.c (ffffffff810cd722)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - kernel/sched/completion.c:completion_done
```
```
In ipc/sem.c (ffffffff81375123)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In drivers/ata/libata-eh.c (ffffffff8165f7bf)
Location: include/linux/spinlock.h:380
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
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
In kernel/sched/completion.c (ffffffff810ca152)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/sched/completion.c:completion_done
```
```
In ipc/sem.c (ffffffff81388b5c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In drivers/ata/libata-eh.c (ffffffff81674202)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
