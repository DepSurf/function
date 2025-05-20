# Function: <code>amd_brs_disable_all</code>

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
void amd_brs_disable_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/brs.c (ffffffff8100b720)
Location: arch/x86/events/amd/brs.c:191
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100b720-ffffffff8100b756: amd_brs_disable_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_brs_disable_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/brs.c (ffffffff8100e050)
Location: arch/x86/events/amd/brs.c:258
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100e050-ffffffff8100e086: amd_brs_disable_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_brs_disable_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/brs.c (ffffffff8100d6c0)
Location: arch/x86/events/amd/brs.c:255
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100d6c0-ffffffff8100d6f6: amd_brs_disable_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_brs_disable_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/brs.c (ffffffff81012f00)
Location: arch/x86/events/amd/brs.c:255
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_handle_irq
```
**Symbols:**

```
ffffffff81012f00-ffffffff81012f36: amd_brs_disable_all (STB_GLOBAL)
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
