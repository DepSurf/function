# Function: <code>osnoise_trace_irq_exit</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void osnoise_trace_irq_exit(int id, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_osnoise.c (0)
Location: kernel/trace/trace_osnoise.c:940
Inline: False
Direct callers:
  - arch/x86/kernel/trace.c:trace_intel_irq_exit
  - kernel/trace/trace_osnoise.c:trace_irqexit_callback
```
**Symbols:**

```
ffffffff820dc91e-ffffffff820dc933: osnoise_trace_irq_exit.cold (STB_LOCAL)
ffffffff81299080-ffffffff812991e3: osnoise_trace_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void osnoise_trace_irq_exit(int id, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_osnoise.c (0)
Location: kernel/trace/trace_osnoise.c:940
Inline: False
Direct callers:
  - arch/x86/kernel/trace.c:trace_intel_irq_exit
  - kernel/trace/trace_osnoise.c:trace_irqexit_callback
```
**Symbols:**

```
ffffffff821b8720-ffffffff821b8735: osnoise_trace_irq_exit.cold (STB_LOCAL)
ffffffff812b46f0-ffffffff812b4867: osnoise_trace_irq_exit (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
