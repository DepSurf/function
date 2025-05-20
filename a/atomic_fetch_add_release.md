# Function: <code>atomic_fetch_add_release</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8119353e)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kprobe_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811944ee)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kprobe_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bd38e)
Location: include/linux/atomic/atomic-instrumented.h:102
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kprobe_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff81268d07)
Location: include/linux/atomic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/trace/rethook.c:rethook_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812bafc7)
Location: include/linux/atomic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/trace/rethook.c:rethook_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812debc7)
Location: include/linux/atomic/atomic-instrumented.h:231
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/trace/rethook.c:rethook_flush_task
```
</details>
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b55fc)
Location: include/linux/atomic-fallback.h:157
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
```
</details>
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
