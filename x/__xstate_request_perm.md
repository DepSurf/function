# Function: <code>__xstate_request_perm</code>

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
int __xstate_request_perm(u64 permitted, u64 requested, bool guest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055b70)
Location: arch/x86/kernel/fpu/xstate.c:1538
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
**Symbols:**

```
ffffffff81055b70-ffffffff81055daa: __xstate_request_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __xstate_request_perm(u64 permitted, u64 requested, bool guest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810639c0)
Location: arch/x86/kernel/fpu/xstate.c:1584
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
**Symbols:**

```
ffffffff810639c0-ffffffff81063bfa: __xstate_request_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __xstate_request_perm(u64 permitted, u64 requested, bool guest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065310)
Location: arch/x86/kernel/fpu/xstate.c:1589
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
**Symbols:**

```
ffffffff81065310-ffffffff8106554d: __xstate_request_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __xstate_request_perm(u64 permitted, u64 requested, bool guest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c250)
Location: arch/x86/kernel/fpu/xstate.c:1585
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
**Symbols:**

```
ffffffff8106c250-ffffffff8106c391: __xstate_request_perm (STB_LOCAL)
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
