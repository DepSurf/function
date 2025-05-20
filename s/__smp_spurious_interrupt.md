# Function: <code>__smp_spurious_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __smp_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052c80)
Location: arch/x86/kernel/apic/apic.c:1810
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
```
**Symbols:**

```
ffffffff81052c80-ffffffff81052ceb: __smp_spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __smp_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052db0)
Location: arch/x86/kernel/apic/apic.c:1849
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
```
**Symbols:**

```
ffffffff81052db0-ffffffff81052e18: __smp_spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __smp_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055aa0)
Location: arch/x86/kernel/apic/apic.c:1847
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
```
**Symbols:**

```
ffffffff81055aa0-ffffffff81055b08: __smp_spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __smp_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810554d0)
Location: arch/x86/kernel/apic/apic.c:1923
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
```
**Symbols:**

```
ffffffff810554d0-ffffffff81055538: __smp_spurious_interrupt (STB_LOCAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
