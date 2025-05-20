# Function: <code>xstate_calculate_size</code>

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
unsigned int xstate_calculate_size(u64 xfeatures, bool compacted);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055bc7)
Location: arch/x86/kernel/fpu/xstate.c:564
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff81055800-ffffffff810558ae: xstate_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063a17)
Location: arch/x86/kernel/fpu/xstate.c:563
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065367)
Location: arch/x86/kernel/fpu/xstate.c:563
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int xstate_calculate_size(u64 xfeatures, bool compacted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c190)
Location: arch/x86/kernel/fpu/xstate.c:559
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff8106c190-ffffffff8106c23e: xstate_calculate_size (STB_LOCAL)
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
</ul>
