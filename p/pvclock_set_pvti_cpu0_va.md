# Function: <code>pvclock_set_pvti_cpu0_va</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8106bb10)
Location: arch/x86/kernel/pvclock.c:150
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
```
**Symbols:**

```
ffffffff8106bb10-ffffffff8106bb31: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8106e7c0)
Location: arch/x86/kernel/pvclock.c:157
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8106e7c0-ffffffff8106e7e1: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810747e0)
Location: arch/x86/kernel/pvclock.c:157
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810747e0-ffffffff81074801: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pvclock.c (0)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81078350-ffffffff81078363: pvclock_set_pvti_cpu0_va.cold (STB_LOCAL)
ffffffff81078330-ffffffff81078350: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810793a0)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810793a0-ffffffff810793bc: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81080680)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81080680-ffffffff8108069c: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81080290)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81080290-ffffffff810802ac: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81081130)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81081130-ffffffff8108114c: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810900d0)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810900d0-ffffffff810900ec: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810a1040)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810a1040-ffffffff810a106c: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810b8ed0)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810b8ed0-ffffffff810b8efc: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810bc0a0)
Location: arch/x86/kernel/pvclock.c:156
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810bc0a0-ffffffff810bc0cc: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810c3220)
Location: arch/x86/kernel/pvclock.c:156
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810c3220-ffffffff810c324c: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810783a0)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810783a0-ffffffff810783bc: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81067c50)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81067c50-ffffffff81067c6c: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff81078350)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81078350-ffffffff8107836c: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info *pvti);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8107a450)
Location: arch/x86/kernel/pvclock.c:146
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8107a450-ffffffff8107a46c: pvclock_set_pvti_cpu0_va (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
