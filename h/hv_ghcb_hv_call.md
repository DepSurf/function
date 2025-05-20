# Function: <code>hv_ghcb_hv_call</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103ee22)
Location: arch/x86/hyperv/ivm.c:111
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81047de0)
Location: arch/x86/hyperv/ivm.c:111
Inline: True
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
**Symbols:**

```
ffffffff81047de0-ffffffff81047e5f: hv_ghcb_hv_call.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048190)
Location: arch/x86/hyperv/ivm.c:114
Inline: True
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
**Symbols:**

```
ffffffff81048190-ffffffff8104820f: hv_ghcb_hv_call.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8104eb70)
Location: arch/x86/hyperv/ivm.c:122
Inline: True
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
**Symbols:**

```
ffffffff8104eb70-ffffffff8104ebef: hv_ghcb_hv_call.constprop.0 (STB_LOCAL)
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
