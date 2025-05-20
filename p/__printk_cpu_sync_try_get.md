# Function: <code>__printk_cpu_sync_try_get</code>

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
int __printk_cpu_sync_try_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115ac50)
Location: kernel/printk/printk.c:3872
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8115ac50-ffffffff8115ac9c: __printk_cpu_sync_try_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __printk_cpu_sync_try_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118d180)
Location: kernel/printk/printk.c:4135
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8118d180-ffffffff8118d1cc: __printk_cpu_sync_try_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __printk_cpu_sync_try_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119e940)
Location: kernel/printk/printk.c:4176
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8119e940-ffffffff8119e98c: __printk_cpu_sync_try_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __printk_cpu_sync_try_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811adb00)
Location: kernel/printk/printk.c:4293
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
  - lib/dump_stack.c:dump_stack_lvl
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff811adb00-ffffffff811adb4c: __printk_cpu_sync_try_get (STB_GLOBAL)
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
