# Function: <code>fpu__xstate_clear_all_cpu_caps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b520)
Location: arch/x86/kernel/fpu/xstate.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:x86_noxsave_setup
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8103b520-ffffffff8103b5db: fpu__xstate_clear_all_cpu_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ae70)
Location: arch/x86/kernel/fpu/xstate.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8103ae70-ffffffff8103af7b: fpu__xstate_clear_all_cpu_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103a710)
Location: arch/x86/kernel/fpu/xstate.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8103a710-ffffffff8103a85b: fpu__xstate_clear_all_cpu_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038660)
Location: arch/x86/kernel/fpu/xstate.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff81038660-ffffffff810387bb: fpu__xstate_clear_all_cpu_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fpu__xstate_clear_all_cpu_caps();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff826b42dd)
Location: arch/x86/kernel/fpu/xstate.c:73
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff8103a8a0-ffffffff8103a8b5: fpu__xstate_clear_all_cpu_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fpu__xstate_clear_all_cpu_caps();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff826ddab1)
Location: arch/x86/kernel/fpu/xstate.c:73
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff8103bda0-ffffffff8103bdb5: fpu__xstate_clear_all_cpu_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fpu__xstate_clear_all_cpu_caps();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff82893ef9)
Location: arch/x86/kernel/fpu/xstate.c:73
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff8103d260-ffffffff8103d275: fpu__xstate_clear_all_cpu_caps (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
