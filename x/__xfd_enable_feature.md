# Function: <code>__xfd_enable_feature</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __xfd_enable_feature(u64 xfd_err, struct fpu_guest *guest_fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:1628
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_enable_guest_xfd_features
  - arch/x86/kernel/fpu/xstate.c:xfd_enable_feature
```
**Symbols:**

```
ffffffff81e499d8-ffffffff81e49a08: __xfd_enable_feature.cold (STB_LOCAL)
ffffffff81057080-ffffffff81057189: __xfd_enable_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __xfd_enable_feature(u64 xfd_err, struct fpu_guest *guest_fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:1674
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_enable_guest_xfd_features
  - arch/x86/kernel/fpu/xstate.c:xfd_enable_feature
```
**Symbols:**

```
ffffffff820526fd-ffffffff82052712: __xfd_enable_feature.cold (STB_LOCAL)
ffffffff810647a0-ffffffff810648c7: __xfd_enable_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __xfd_enable_feature(u64 xfd_err, struct fpu_guest *guest_fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:1679
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_enable_guest_xfd_features
  - arch/x86/kernel/fpu/xstate.c:xfd_enable_feature
```
**Symbols:**

```
ffffffff820d0bcb-ffffffff820d0bdf: __xfd_enable_feature.cold (STB_LOCAL)
ffffffff810660b0-ffffffff810661c7: __xfd_enable_feature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __xfd_enable_feature(u64 xfd_err, struct fpu_guest *guest_fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:1675
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_enable_guest_xfd_features
  - arch/x86/kernel/fpu/xstate.c:xfd_enable_feature
```
**Symbols:**

```
ffffffff821ab6f4-ffffffff821ab708: __xfd_enable_feature.cold (STB_LOCAL)
ffffffff8106d530-ffffffff8106d647: __xfd_enable_feature (STB_GLOBAL)
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
