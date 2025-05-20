# Function: <code>__printk_cpu_sync_wait</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void __printk_cpu_sync_wait();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115ac30)
Location: kernel/printk/printk.c:3853
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8115ac30-ffffffff8115ac4e: __printk_cpu_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __printk_cpu_sync_wait();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118d150)
Location: kernel/printk/printk.c:4116
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8118d150-ffffffff8118d16e: __printk_cpu_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __printk_cpu_sync_wait();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119e910)
Location: kernel/printk/printk.c:4157
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8119e910-ffffffff8119e92e: __printk_cpu_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __printk_cpu_sync_wait();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811adad0)
Location: kernel/printk/printk.c:4274
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff811adad0-ffffffff811adaee: __printk_cpu_sync_wait (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
