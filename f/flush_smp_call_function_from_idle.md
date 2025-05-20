# Function: <code>flush_smp_call_function_from_idle</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_smp_call_function_from_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115fca0)
Location: kernel/smp.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8115fca0-ffffffff8115fced: flush_smp_call_function_from_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_smp_call_function_from_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115bc40)
Location: kernel/smp.c:444
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8115bc40-ffffffff8115bca1: flush_smp_call_function_from_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_smp_call_function_from_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115ce60)
Location: kernel/smp.c:684
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8115ce60-ffffffff8115cece: flush_smp_call_function_from_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_smp_call_function_from_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81182160)
Location: kernel/smp.c:684
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81182160-ffffffff811821ce: flush_smp_call_function_from_idle (STB_GLOBAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
