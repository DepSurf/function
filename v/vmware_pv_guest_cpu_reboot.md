# Function: <code>vmware_pv_guest_cpu_reboot</code>

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
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810677e0)
Location: arch/x86/kernel/cpu/vmware.c:274
Inline: False
```
**Symbols:**

```
ffffffff810677e0-ffffffff81067801: vmware_pv_guest_cpu_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810695a0)
Location: arch/x86/kernel/cpu/vmware.c:275
Inline: False
```
**Symbols:**

```
ffffffff810695a0-ffffffff810695c1: vmware_pv_guest_cpu_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff8106a030)
Location: arch/x86/kernel/cpu/vmware.c:276
Inline: False
```
**Symbols:**

```
ffffffff8106a030-ffffffff8106a051: vmware_pv_guest_cpu_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:276
Inline: False
```
**Symbols:**

```
ffffffff81074800-ffffffff81074831: vmware_pv_guest_cpu_reboot (STB_LOCAL)
ffffffff81c9cfa2-ffffffff81c9cfb6: vmware_pv_guest_cpu_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:276
Inline: False
```
**Symbols:**

```
ffffffff81083140-ffffffff8108317b: vmware_pv_guest_cpu_reboot (STB_LOCAL)
ffffffff81e4c360-ffffffff81e4c374: vmware_pv_guest_cpu_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:276
Inline: False
```
**Symbols:**

```
ffffffff81095cc0-ffffffff81095cfb: vmware_pv_guest_cpu_reboot (STB_LOCAL)
ffffffff820539ac-ffffffff820539c0: vmware_pv_guest_cpu_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:276
Inline: False
```
**Symbols:**

```
ffffffff81098b90-ffffffff81098bcb: vmware_pv_guest_cpu_reboot (STB_LOCAL)
ffffffff820d1f70-ffffffff820d1f84: vmware_pv_guest_cpu_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vmware_pv_guest_cpu_reboot(void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:276
Inline: False
```
**Symbols:**

```
ffffffff810a0130-ffffffff810a016b: vmware_pv_guest_cpu_reboot (STB_LOCAL)
ffffffff821acbd4-ffffffff821acbe8: vmware_pv_guest_cpu_reboot.cold (STB_LOCAL)
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
