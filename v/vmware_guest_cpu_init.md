# Function: <code>vmware_guest_cpu_init</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81067820)
Location: arch/x86/kernel/cpu/vmware.c:268
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810695e0)
Location: arch/x86/kernel/cpu/vmware.c:269
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff8106a070)
Location: arch/x86/kernel/cpu/vmware.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vmware_guest_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff810745d0-ffffffff8107467d: vmware_guest_cpu_init (STB_LOCAL)
ffffffff81c9ced9-ffffffff81c9cf3b: vmware_guest_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vmware_guest_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81082e50-ffffffff81082f13: vmware_guest_cpu_init (STB_LOCAL)
ffffffff81e4c26e-ffffffff81e4c2d2: vmware_guest_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void vmware_guest_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81095970-ffffffff81095a33: vmware_guest_cpu_init (STB_LOCAL)
ffffffff820538e0-ffffffff82053944: vmware_guest_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vmware_guest_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff810989b0-ffffffff81098a79: vmware_guest_cpu_init (STB_LOCAL)
ffffffff820d1ef6-ffffffff820d1f5c: vmware_guest_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vmware_guest_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8109ff50-ffffffff810a0019: vmware_guest_cpu_init (STB_LOCAL)
ffffffff821acb5a-ffffffff821acbc0: vmware_guest_cpu_init.cold (STB_LOCAL)
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
