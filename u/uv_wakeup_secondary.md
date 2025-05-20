# Function: <code>uv_wakeup_secondary</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d060)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:517
Inline: False
```
**Symbols:**

```
ffffffff8106d060-ffffffff8106d15d: uv_wakeup_secondary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074aa0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:542
Inline: False
```
**Symbols:**

```
ffffffff81074aa0-ffffffff81074b9d: uv_wakeup_secondary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810753f0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:700
Inline: False
```
**Symbols:**

```
ffffffff810753f0-ffffffff810754e9: uv_wakeup_secondary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075e90)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:696
Inline: False
```
**Symbols:**

```
ffffffff81075e90-ffffffff81075f8e: uv_wakeup_secondary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:696
Inline: False
```
**Symbols:**

```
ffffffff81083460-ffffffff8108358f: uv_wakeup_secondary (STB_LOCAL)
ffffffff81c9e6d6-ffffffff81c9e747: uv_wakeup_secondary.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:702
Inline: False
```
**Symbols:**

```
ffffffff81093310-ffffffff8109343b: uv_wakeup_secondary (STB_LOCAL)
ffffffff81e4db1e-ffffffff81e4db8d: uv_wakeup_secondary.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:702
Inline: False
```
**Symbols:**

```
ffffffff810a86e0-ffffffff810a880b: uv_wakeup_secondary (STB_LOCAL)
ffffffff82053efe-ffffffff82053f6d: uv_wakeup_secondary.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:703
Inline: False
```
**Symbols:**

```
ffffffff810ab950-ffffffff810aba7b: uv_wakeup_secondary (STB_LOCAL)
ffffffff820d2520-ffffffff820d258f: uv_wakeup_secondary.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int uv_wakeup_secondary(u32 phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:704
Inline: False
```
**Symbols:**

```
ffffffff810b27c0-ffffffff810b28e8: uv_wakeup_secondary (STB_LOCAL)
ffffffff821ad251-ffffffff821ad2c0: uv_wakeup_secondary.cold (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uv_wakeup_secondary(int phys_apicid, long unsigned int start_rip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e720)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:517
Inline: False
```
**Symbols:**

```
ffffffff8106e720-ffffffff8106e81d: uv_wakeup_secondary (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<code>int phys_apicid</code> ➡️ <code>u32 phys_apicid</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
