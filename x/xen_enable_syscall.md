# Function: <code>xen_enable_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101d760)
Location: arch/x86/xen/setup.c:1007
Inline: True
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101d760-ffffffff8101d813: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101cb10)
Location: arch/x86/xen/setup.c:994
Inline: True
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101cb10-ffffffff8101cbc2: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101d230)
Location: arch/x86/xen/setup.c:994
Inline: True
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101d230-ffffffff8101d2e2: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101bc60)
Location: arch/x86/xen/setup.c:986
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101bc60-ffffffff8101bcfc: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101c960)
Location: arch/x86/xen/setup.c:983
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101c960-ffffffff8101c9f8: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (0)
Location: arch/x86/xen/setup.c:983
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101d462-ffffffff8101d475: xen_enable_syscall.cold.4 (STB_LOCAL)
ffffffff8101d380-ffffffff8101d40c: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101cc6d)
Location: arch/x86/xen/setup.c:954
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101ccf2-ffffffff8101cd05: xen_enable_syscall.cold.4 (STB_LOCAL)
ffffffff8101cc10-ffffffff8101cc9c: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101e79c)
Location: arch/x86/xen/setup.c:967
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101e832-ffffffff8101e845: xen_enable_syscall.cold (STB_LOCAL)
ffffffff8101e750-ffffffff8101e7dc: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101f11c)
Location: arch/x86/xen/setup.c:967
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f1b2-ffffffff8101f1c5: xen_enable_syscall.cold (STB_LOCAL)
ffffffff8101f0d0-ffffffff8101f15c: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8102171c)
Location: arch/x86/xen/setup.c:968
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff810217b2-ffffffff810217c5: xen_enable_syscall.cold (STB_LOCAL)
ffffffff810216d0-ffffffff8102175c: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81021e6c)
Location: arch/x86/xen/setup.c:930
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81bd2a20-ffffffff81bd2a33: xen_enable_syscall.cold (STB_LOCAL)
ffffffff81021e20-ffffffff81021eac: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff810241fc)
Location: arch/x86/xen/setup.c:930
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81bc4bbe-ffffffff81bc4bd1: xen_enable_syscall.cold (STB_LOCAL)
ffffffff810241b0-ffffffff8102423c: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff810285dc)
Location: arch/x86/xen/setup.c:930
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81c972a3-ffffffff81c972b6: xen_enable_syscall.cold (STB_LOCAL)
ffffffff81028590-ffffffff8102861c: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8102cc5d)
Location: arch/x86/xen/setup.c:926
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81e4676f-ffffffff81e46782: xen_enable_syscall.cold (STB_LOCAL)
ffffffff8102cc10-ffffffff8102ccb0: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81033e30)
Location: arch/x86/xen/setup.c:919
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81033e30-ffffffff81033ed3: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81033dc0)
Location: arch/x86/xen/setup.c:929
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
**Symbols:**

```
ffffffff81033dc0-ffffffff81033e63: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8103a0c0)
Location: arch/x86/xen/setup.c:935
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
**Symbols:**

```
ffffffff8103a0c0-ffffffff8103a163: xen_enable_syscall (STB_GLOBAL)
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

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101f27c)
Location: arch/x86/xen/setup.c:967
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f312-ffffffff8101f325: xen_enable_syscall.cold (STB_LOCAL)
ffffffff8101f230-ffffffff8101f2bc: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101f0dc)
Location: arch/x86/xen/setup.c:967
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f172-ffffffff8101f185: xen_enable_syscall.cold (STB_LOCAL)
ffffffff8101f090-ffffffff8101f11c: xen_enable_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_syscall();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101f32c)
Location: arch/x86/xen/setup.c:967
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f3c2-ffffffff8101f3d5: xen_enable_syscall.cold (STB_LOCAL)
ffffffff8101f2e0-ffffffff8101f36c: xen_enable_syscall (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
