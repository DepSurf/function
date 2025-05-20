# Function: <code>queued_spin_unlock_wait</code>

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
In kernel/exit.c (ffffffff81083984)
Location: include/asm-generic/qspinlock.h:108
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/task_work.c (ffffffff8109e92a)
Location: include/asm-generic/qspinlock.h:108
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/sched/completion.c (ffffffff810c3be1)
Location: include/asm-generic/qspinlock.h:108
Inline: True
```
```
In ipc/sem.c (ffffffff81326e0d)
Location: include/asm-generic/qspinlock.h:108
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In drivers/ata/libata-eh.c (ffffffff815d4bea)
Location: include/asm-generic/qspinlock.h:108
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void queued_spin_unlock_wait(struct qspinlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810cf0a0)
Location: kernel/locking/qspinlock.c:360
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/task_work.c:task_work_run
  - kernel/sched/completion.c:completion_done
  - ipc/sem.c:exit_sem
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff810cf0a0-ffffffff810cf0c9: queued_spin_unlock_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void queued_spin_unlock_wait(struct qspinlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810d5a90)
Location: kernel/locking/qspinlock.c:360
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/task_work.c:task_work_run
  - kernel/sched/core.c:do_task_dead
  - kernel/sched/completion.c:completion_done
  - ipc/sem.c:exit_sem
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff810d5a90-ffffffff810d5ab9: queued_spin_unlock_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void queued_spin_unlock_wait(struct qspinlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810d4a10)
Location: kernel/locking/qspinlock.c:361
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/task_work.c:task_work_run
  - kernel/sched/core.c:do_task_dead
  - kernel/sched/completion.c:completion_done
  - ipc/sem.c:exit_sem
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff810d4a10-ffffffff810d4a39: queued_spin_unlock_wait (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
