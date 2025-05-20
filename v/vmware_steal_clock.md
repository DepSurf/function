# Function: <code>vmware_steal_clock</code>

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
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810676b0)
Location: arch/x86/kernel/cpu/vmware.c:216
Inline: False
```
**Symbols:**

```
ffffffff810676b0-ffffffff810676f1: vmware_steal_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810692f0)
Location: arch/x86/kernel/cpu/vmware.c:217
Inline: False
```
**Symbols:**

```
ffffffff810692f0-ffffffff81069331: vmware_steal_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069d80)
Location: arch/x86/kernel/cpu/vmware.c:218
Inline: False
```
**Symbols:**

```
ffffffff81069d80-ffffffff81069dc1: vmware_steal_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:218
Inline: False
```
**Symbols:**

```
ffffffff810746c0-ffffffff81074767: vmware_steal_clock (STB_LOCAL)
ffffffff81c9cf4e-ffffffff81c9cf78: vmware_steal_clock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:218
Inline: False
```
**Symbols:**

```
ffffffff81082ff0-ffffffff810830a3: vmware_steal_clock (STB_LOCAL)
ffffffff81e4c30c-ffffffff81e4c336: vmware_steal_clock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:218
Inline: False
```
**Symbols:**

```
ffffffff81095b50-ffffffff81095c03: vmware_steal_clock (STB_LOCAL)
ffffffff82053958-ffffffff82053982: vmware_steal_clock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:218
Inline: False
```
**Symbols:**

```
ffffffff810988e0-ffffffff81098993: vmware_steal_clock (STB_LOCAL)
ffffffff820d1ecc-ffffffff820d1ef6: vmware_steal_clock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
uint64_t vmware_steal_clock(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:218
Inline: False
```
**Symbols:**

```
ffffffff8109fe80-ffffffff8109ff33: vmware_steal_clock (STB_LOCAL)
ffffffff821acb30-ffffffff821acb5a: vmware_steal_clock.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
