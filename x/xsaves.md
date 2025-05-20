# Function: <code>xsaves</code>

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
void xsaves(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104c350)
Location: arch/x86/kernel/fpu/xstate.c:1212
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read_xsave
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xsaves
```
**Symbols:**

```
ffffffff8104c350-ffffffff8104c38e: xsaves (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xsaves(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81056f20)
Location: arch/x86/kernel/fpu/xstate.c:1310
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xsaves
```
**Symbols:**

```
ffffffff81056f20-ffffffff81056f69: xsaves (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xsaves(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064600)
Location: arch/x86/kernel/fpu/xstate.c:1356
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xsaves
```
**Symbols:**

```
ffffffff81064600-ffffffff81064649: xsaves (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xsaves(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065f10)
Location: arch/x86/kernel/fpu/xstate.c:1361
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xsaves
```
**Symbols:**

```
ffffffff81065f10-ffffffff81065f59: xsaves (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xsaves(struct xregs_state *xstate, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106d390)
Location: arch/x86/kernel/fpu/xstate.c:1360
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_xsaves
```
**Symbols:**

```
ffffffff8106d390-ffffffff8106d3d9: xsaves (STB_GLOBAL)
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
