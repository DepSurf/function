# Function: <code>wakeup_cpu_via_vmgexit</code>

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
int wakeup_cpu_via_vmgexit(int apic_id, long unsigned int start_ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:985
Inline: False
```
**Symbols:**

```
ffffffff810a4dc0-ffffffff810a52b8: wakeup_cpu_via_vmgexit (STB_LOCAL)
ffffffff81e4ee64-ffffffff81e4eee5: wakeup_cpu_via_vmgexit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int wakeup_cpu_via_vmgexit(int apic_id, long unsigned int start_ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:985
Inline: False
```
**Symbols:**

```
ffffffff810bd4c0-ffffffff810bda32: wakeup_cpu_via_vmgexit (STB_LOCAL)
ffffffff8205464a-ffffffff8205465f: wakeup_cpu_via_vmgexit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int wakeup_cpu_via_vmgexit(int apic_id, long unsigned int start_ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:943
Inline: False
```
**Symbols:**

```
ffffffff810c0b30-ffffffff810c10a5: wakeup_cpu_via_vmgexit (STB_LOCAL)
ffffffff820d2c3b-ffffffff820d2c58: wakeup_cpu_via_vmgexit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int wakeup_cpu_via_vmgexit(u32 apic_id, long unsigned int start_ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:969
Inline: False
```
**Symbols:**

```
ffffffff810c7f90-ffffffff810c8505: wakeup_cpu_via_vmgexit (STB_LOCAL)
ffffffff821ada9d-ffffffff821adaba: wakeup_cpu_via_vmgexit.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int apic_id</code> ➡️ <code>u32 apic_id</code>
</li>
</ul>
</details>
</li>
</ul>
