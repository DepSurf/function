# Function: <code>xen_enable_sysenter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101d6e0)
Location: arch/x86/xen/setup.c:988
Inline: True
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101d6e0-ffffffff8101d75a: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101ca90)
Location: arch/x86/xen/setup.c:975
Inline: True
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101ca90-ffffffff8101cb09: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101d1b0)
Location: arch/x86/xen/setup.c:975
Inline: True
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101d1b0-ffffffff8101d229: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101bbf0)
Location: arch/x86/xen/setup.c:967
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101bbf0-ffffffff8101bc5e: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8101c8e0)
Location: arch/x86/xen/setup.c:964
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101c8e0-ffffffff8101c93a: xen_enable_sysenter.part.3 (STB_LOCAL)
ffffffff8101c940-ffffffff8101c960: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826d4853)
Location: arch/x86/xen/setup.c:964
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101d300-ffffffff8101d35c: xen_enable_sysenter.part.2 (STB_LOCAL)
ffffffff8101d360-ffffffff8101d37f: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8288a808)
Location: arch/x86/xen/setup.c:935
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101cb90-ffffffff8101cbec: xen_enable_sysenter.part.2 (STB_LOCAL)
ffffffff8101cbf0-ffffffff8101cc0f: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a1bc5)
Location: arch/x86/xen/setup.c:948
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101e6d0-ffffffff8101e72c: xen_enable_sysenter.part.0 (STB_LOCAL)
ffffffff8101e730-ffffffff8101e74f: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a4c85)
Location: arch/x86/xen/setup.c:948
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f050-ffffffff8101f0ac: xen_enable_sysenter.part.0 (STB_LOCAL)
ffffffff8101f0b0-ffffffff8101f0cf: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81021660)
Location: arch/x86/xen/setup.c:949
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81021660-ffffffff810216c8: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81021db0)
Location: arch/x86/xen/setup.c:915
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81021db0-ffffffff81021e18: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81024140)
Location: arch/x86/xen/setup.c:915
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81024140-ffffffff810241a8: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81028520)
Location: arch/x86/xen/setup.c:915
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81028520-ffffffff81028588: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8102cb90)
Location: arch/x86/xen/setup.c:911
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8102cb90-ffffffff8102cc0b: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81033da0)
Location: arch/x86/xen/setup.c:912
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff81033da0-ffffffff81033e14: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81033d30)
Location: arch/x86/xen/setup.c:922
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
**Symbols:**

```
ffffffff81033d30-ffffffff81033da4: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8103a030)
Location: arch/x86/xen/setup.c:928
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
**Symbols:**

```
ffffffff8103a030-ffffffff8103a0a4: xen_enable_sysenter (STB_GLOBAL)
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
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82892c9d)
Location: arch/x86/xen/setup.c:948
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f1b0-ffffffff8101f20c: xen_enable_sysenter.part.0 (STB_LOCAL)
ffffffff8101f210-ffffffff8101f22f: xen_enable_sysenter (STB_GLOBAL)
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
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a5c85)
Location: arch/x86/xen/setup.c:948
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f010-ffffffff8101f06c: xen_enable_sysenter.part.0 (STB_LOCAL)
ffffffff8101f070-ffffffff8101f08f: xen_enable_sysenter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_enable_sysenter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a5c59)
Location: arch/x86/xen/setup.c:948
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
**Symbols:**

```
ffffffff8101f260-ffffffff8101f2bc: xen_enable_sysenter.part.0 (STB_LOCAL)
ffffffff8101f2c0-ffffffff8101f2df: xen_enable_sysenter (STB_GLOBAL)
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
