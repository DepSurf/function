# Function: <code>fpu_idle_fpregs</code>

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
void fpu_idle_fpregs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff820bcc40)
Location: arch/x86/kernel/fpu/core.c:856
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
```
**Symbols:**

```
ffffffff820bcc40-ffffffff820bcc70: fpu_idle_fpregs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fpu_idle_fpregs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8213e600)
Location: arch/x86/kernel/fpu/core.c:856
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
```
**Symbols:**

```
ffffffff8213e600-ffffffff8213e630: fpu_idle_fpregs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fpu_idle_fpregs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff822205f0)
Location: arch/x86/kernel/fpu/core.c:909
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
```
**Symbols:**

```
ffffffff822205f0-ffffffff82220620: fpu_idle_fpregs (STB_GLOBAL)
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
