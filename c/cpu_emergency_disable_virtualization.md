# Function: <code>cpu_emergency_disable_virtualization</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_emergency_disable_virtualization();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81097e61)
Location: arch/x86/kernel/reboot.c:839
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
Direct callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81098060-ffffffff810980fb: cpu_emergency_disable_virtualization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_emergency_disable_virtualization();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8109af01)
Location: arch/x86/kernel/reboot.c:839
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
Direct callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff8109b100-ffffffff8109b1a4: cpu_emergency_disable_virtualization (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_emergency_disable_virtualization();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff810a260a)
Location: arch/x86/kernel/reboot.c:599
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff810a2670-ffffffff810a269c: cpu_emergency_disable_virtualization (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
