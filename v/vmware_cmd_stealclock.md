# Function: <code>vmware_cmd_stealclock</code>

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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81067680)
Location: arch/x86/kernel/cpu/vmware.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_register_steal_time
```
**Symbols:**

```
ffffffff81067680-ffffffff810676ab: vmware_cmd_stealclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810692c0)
Location: arch/x86/kernel/cpu/vmware.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_register_steal_time
```
**Symbols:**

```
ffffffff810692c0-ffffffff810692eb: vmware_cmd_stealclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069d50)
Location: arch/x86/kernel/cpu/vmware.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_register_steal_time
```
**Symbols:**

```
ffffffff81069d50-ffffffff81069d7b: vmware_cmd_stealclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81074430)
Location: arch/x86/kernel/cpu/vmware.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
```
**Symbols:**

```
ffffffff81074430-ffffffff8107445b: vmware_cmd_stealclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082c80)
Location: arch/x86/kernel/cpu/vmware.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
```
**Symbols:**

```
ffffffff81082c80-ffffffff81082cba: vmware_cmd_stealclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81095770)
Location: arch/x86/kernel/cpu/vmware.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
```
**Symbols:**

```
ffffffff81095770-ffffffff810957aa: vmware_cmd_stealclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810986e0)
Location: arch/x86/kernel/cpu/vmware.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
```
**Symbols:**

```
ffffffff810986e0-ffffffff8109871a: vmware_cmd_stealclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fc80)
Location: arch/x86/kernel/cpu/vmware.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot
  - arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init
```
**Symbols:**

```
ffffffff8109fc80-ffffffff8109fcba: vmware_cmd_stealclock (STB_LOCAL)
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
