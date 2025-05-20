# Function: <code>vmware_register_steal_time</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmware_register_steal_time();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81067700)
Location: arch/x86/kernel/cpu/vmware.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81067700-ffffffff8106777e: vmware_register_steal_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmware_register_steal_time();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810694c0)
Location: arch/x86/kernel/cpu/vmware.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff810694c0-ffffffff8106953e: vmware_register_steal_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmware_register_steal_time();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069f40)
Location: arch/x86/kernel/cpu/vmware.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_online
  - arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81069f40-ffffffff81069fbd: vmware_register_steal_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81074601)
Location: arch/x86/kernel/cpu/vmware.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082e89)
Location: arch/x86/kernel/cpu/vmware.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
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
In arch/x86/kernel/cpu/vmware.c (ffffffff810959a9)
Location: arch/x86/kernel/cpu/vmware.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
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
In arch/x86/kernel/cpu/vmware.c (ffffffff810989f0)
Location: arch/x86/kernel/cpu/vmware.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109ff90)
Location: arch/x86/kernel/cpu/vmware.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
