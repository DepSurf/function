# Function: <code>fpstate_init_user</code>

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
void fpstate_init_user(struct fpstate *fpstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8105294c)
Location: arch/x86/kernel/fpu/core.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff81053300-ffffffff8105333d: fpstate_init_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fpstate_init_user(struct fpstate *fpstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8105ffbc)
Location: arch/x86/kernel/fpu/core.c:503
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff81060c10-ffffffff81060c4d: fpstate_init_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fpstate_init_user(struct fpstate *fpstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8106172c)
Location: arch/x86/kernel/fpu/core.c:503
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff81062610-ffffffff8106264d: fpstate_init_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fpstate_init_user(struct fpstate *fpstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8106883c)
Location: arch/x86/kernel/fpu/core.c:504
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff81069730-ffffffff8106976d: fpstate_init_user (STB_GLOBAL)
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
