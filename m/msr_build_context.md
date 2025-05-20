# Function: <code>msr_build_context</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818d788d)
Location: arch/x86/power/cpu.c:401
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff818d788d-ffffffff818d7952: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81909bcd)
Location: arch/x86/power/cpu.c:397
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff81909bcd-ffffffff81909c92: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81bba4e1)
Location: arch/x86/power/cpu.c:403
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff81bba4e1-ffffffff81bba5a6: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81c34b11)
Location: arch/x86/power/cpu.c:403
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff81c34b11-ffffffff81c34bd6: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81c26ee2)
Location: arch/x86/power/cpu.c:399
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff81c26ee2-ffffffff81c26fa7: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81d44e6d)
Location: arch/x86/power/cpu.c:400
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff81d44e6d-ffffffff81d44f32: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int msr_build_context(const u32 *msr_id, const int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:409
Inline: False
Direct callers:
  - arch/x86/power/cpu.c:pm_check_save_msr
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff81e42130-ffffffff81e42258: msr_build_context (STB_LOCAL)
ffffffff81f11ddd-ffffffff81f11df3: msr_build_context.cold (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff8201c940)
Location: arch/x86/power/cpu.c:410
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:pm_save_spec_msr
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff8201c940-ffffffff8201ca9f: msr_build_context.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff8209cfd0)
Location: arch/x86/power/cpu.c:373
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:pm_save_spec_msr
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff8209cfd0-ffffffff8209d12f: msr_build_context.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff82174620)
Location: arch/x86/power/cpu.c:373
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:pm_save_spec_msr
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff82174620-ffffffff8217477f: msr_build_context.constprop.0 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818a8f8d)
Location: arch/x86/power/cpu.c:397
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff818a8f8d-ffffffff818a9052: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81863bfd)
Location: arch/x86/power/cpu.c:397
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff81863bfd-ffffffff81863cc2: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818fa5ed)
Location: arch/x86/power/cpu.c:397
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff818fa5ed-ffffffff818fa6b2: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8191b74d)
Location: arch/x86/power/cpu.c:397
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:msr_save_cpuid_features
  - arch/x86/power/cpu.c:msr_initialize_bdw
```
**Symbols:**

```
ffffffff8191b74d-ffffffff8191b812: msr_build_context.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
