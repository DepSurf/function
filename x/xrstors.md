# Function: <code>xrstors</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xrstors(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104c390)
Location: arch/x86/kernel/fpu/xstate.c:1237
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xrstors
```
**Symbols:**

```
ffffffff8104c390-ffffffff8104c3ce: xrstors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xrstors(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81056f70)
Location: arch/x86/kernel/fpu/xstate.c:1334
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xrstors
```
**Symbols:**

```
ffffffff81056f70-ffffffff81056fb9: xrstors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xrstors(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064660)
Location: arch/x86/kernel/fpu/xstate.c:1380
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xrstors
```
**Symbols:**

```
ffffffff81064660-ffffffff810646a9: xrstors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xrstors(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065f70)
Location: arch/x86/kernel/fpu/xstate.c:1385
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xrstors
```
**Symbols:**

```
ffffffff81065f70-ffffffff81065fb9: xrstors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xrstors(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106d3f0)
Location: arch/x86/kernel/fpu/xstate.c:1384
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xrstors
```
**Symbols:**

```
ffffffff8106d3f0-ffffffff8106d439: xrstors (STB_GLOBAL)
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
