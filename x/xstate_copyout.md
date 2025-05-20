# Function: <code>xstate_copyout</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b4e6)
Location: arch/x86/kernel/fpu/xstate.c:922
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
**Symbols:**

```
ffffffff8103ade0-ffffffff8103ae62: xstate_copyout.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ad86)
Location: arch/x86/kernel/fpu/xstate.c:920
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
**Symbols:**

```
ffffffff8103a680-ffffffff8103a702: xstate_copyout.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038bda)
Location: arch/x86/kernel/fpu/xstate.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
**Symbols:**

```
ffffffff81038510-ffffffff81038594: xstate_copyout.part.2 (STB_LOCAL)
```
</details>
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
