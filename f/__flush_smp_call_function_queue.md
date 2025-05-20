# Function: <code>__flush_smp_call_function_queue</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:564
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff811b7a90-ffffffff811b7c3e: __flush_smp_call_function_queue (STB_LOCAL)
ffffffff81e63900-ffffffff81e6395d: __flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:563
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff811f8cd0-ffffffff811f8ebe: __flush_smp_call_function_queue (STB_LOCAL)
ffffffff8205bf7a-ffffffff8205bf8f: __flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:430
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8120e450-ffffffff8120e875: __flush_smp_call_function_queue (STB_LOCAL)
ffffffff820da775-ffffffff820da78a: __flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:445
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81225be0-ffffffff8122601a: __flush_smp_call_function_queue (STB_LOCAL)
ffffffff821b62e5-ffffffff821b62fa: __flush_smp_call_function_queue.cold (STB_LOCAL)
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
