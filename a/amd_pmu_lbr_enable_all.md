# Function: <code>amd_pmu_lbr_enable_all</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_pmu_lbr_enable_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/lbr.c (ffffffff8100da90)
Location: arch/x86/events/amd/lbr.c:389
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100da90-ffffffff8100db8c: amd_pmu_lbr_enable_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_pmu_lbr_enable_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/lbr.c (ffffffff8100d260)
Location: arch/x86/events/amd/lbr.c:389
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100d260-ffffffff8100d35c: amd_pmu_lbr_enable_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_pmu_lbr_enable_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/lbr.c (ffffffff81012aa0)
Location: arch/x86/events/amd/lbr.c:389
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81012aa0-ffffffff81012b9c: amd_pmu_lbr_enable_all (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
