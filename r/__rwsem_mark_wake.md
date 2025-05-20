# Function: <code>__rwsem_mark_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rw_semaphore *__rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d0500)
Location: kernel/locking/rwsem-xadd.c:125
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
**Symbols:**

```
ffffffff810d0500-ffffffff810d0658: __rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d70bd)
Location: kernel/locking/rwsem-xadd.c:124
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
**Symbols:**

```
ffffffff810d6f00-ffffffff810d7061: __rwsem_mark_wake.part.2 (STB_LOCAL)
ffffffff810d7120-ffffffff810d714e: __rwsem_mark_wake.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d60fd)
Location: kernel/locking/rwsem-xadd.c:126
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
**Symbols:**

```
ffffffff810d5f60-ffffffff810d60a1: __rwsem_mark_wake.part.2 (STB_LOCAL)
ffffffff810d6160-ffffffff810d618e: __rwsem_mark_wake.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810de0bd)
Location: kernel/locking/rwsem-xadd.c:127
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
**Symbols:**

```
ffffffff810ddf20-ffffffff810de061: __rwsem_mark_wake.part.2 (STB_LOCAL)
ffffffff810de120-ffffffff810de14e: __rwsem_mark_wake.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810e6722)
Location: kernel/locking/rwsem-xadd.c:127
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
**Symbols:**

```
ffffffff810e6590-ffffffff810e66cf: __rwsem_mark_wake.part.6 (STB_LOCAL)
ffffffff810e6780-ffffffff810e67ae: __rwsem_mark_wake.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810f1b10)
Location: kernel/locking/rwsem-xadd.c:127
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
**Symbols:**

```
ffffffff810f1b10-ffffffff810f1d02: __rwsem_mark_wake (STB_LOCAL)
```
</details>
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
</ul>
