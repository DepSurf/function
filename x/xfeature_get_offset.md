# Function: <code>xfeature_get_offset</code>

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
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810556e0)
Location: arch/x86/kernel/fpu/xstate.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff810556e0-ffffffff810557f2: xfeature_get_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063280)
Location: arch/x86/kernel/fpu/xstate.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff81063280-ffffffff81063392: xfeature_get_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064bd0)
Location: arch/x86/kernel/fpu/xstate.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff81064bd0-ffffffff81064ce2: xfeature_get_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c060)
Location: arch/x86/kernel/fpu/xstate.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xstate_calculate_size
```
**Symbols:**

```
ffffffff8106c060-ffffffff8106c172: xfeature_get_offset (STB_LOCAL)
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
