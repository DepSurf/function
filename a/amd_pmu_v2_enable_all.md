# Function: <code>amd_pmu_v2_enable_all</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_v2_enable_all(int added);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100aba8)
Location: arch/x86/events/amd/core.c:802
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
**Symbols:**

```
ffffffff8100aae0-ffffffff8100ab1d: amd_pmu_v2_enable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_v2_enable_all(int added);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100cabd)
Location: arch/x86/events/amd/core.c:757
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100c710-ffffffff8100c752: amd_pmu_v2_enable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_v2_enable_all(int added);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100c35d)
Location: arch/x86/events/amd/core.c:757
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100bed0-ffffffff8100bf12: amd_pmu_v2_enable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_v2_enable_all(int added);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81011a5d)
Location: arch/x86/events/amd/core.c:759
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff810116b0-ffffffff810116f2: amd_pmu_v2_enable_all (STB_LOCAL)
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
