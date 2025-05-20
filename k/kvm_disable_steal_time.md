# Function: <code>kvm_disable_steal_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063c90)
Location: arch/x86/kernel/kvm.c:419
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
```
**Symbols:**

```
ffffffff81063c90-ffffffff81063cac: kvm_disable_steal_time.part.14 (STB_LOCAL)
ffffffff81063f30-ffffffff81063f4b: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063bf6)
Location: arch/x86/kernel/kvm.c:410
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff810638a0-ffffffff810638bc: kvm_disable_steal_time.part.14 (STB_LOCAL)
ffffffff81063b50-ffffffff81063b6b: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810670b0)
Location: arch/x86/kernel/kvm.c:407
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81066d50-ffffffff81066d6c: kvm_disable_steal_time.part.14 (STB_LOCAL)
ffffffff81067000-ffffffff8106701b: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066380)
Location: arch/x86/kernel/kvm.c:414
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81066030-ffffffff8106604c: kvm_disable_steal_time.part.13 (STB_LOCAL)
ffffffff810662d0-ffffffff810662ec: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106a580)
Location: arch/x86/kernel/kvm.c:421
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81069f80-ffffffff81069f9c: kvm_disable_steal_time.part.11 (STB_LOCAL)
ffffffff8106a4d0-ffffffff8106a4ec: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106d1e0)
Location: arch/x86/kernel/kvm.c:421
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff8106cb90-ffffffff8106cbac: kvm_disable_steal_time.part.13 (STB_LOCAL)
ffffffff8106d130-ffffffff8106d14b: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810733b0)
Location: arch/x86/kernel/kvm.c:412
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81072ca0-ffffffff81072cbc: kvm_disable_steal_time.part.14 (STB_LOCAL)
ffffffff81073300-ffffffff8107331b: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076f40)
Location: arch/x86/kernel/kvm.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81076570-ffffffff8107658c: kvm_disable_steal_time.part.0 (STB_LOCAL)
ffffffff81076e90-ffffffff81076eab: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81077f90)
Location: arch/x86/kernel/kvm.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81077580-ffffffff8107759c: kvm_disable_steal_time.part.0 (STB_LOCAL)
ffffffff81077ee0-ffffffff81077efb: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f270)
Location: arch/x86/kernel/kvm.c:398
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff8107f1b0-ffffffff8107f1d7: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107ef20)
Location: arch/x86/kernel/kvm.c:419
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff8107ee60-ffffffff8107ee87: kvm_disable_steal_time (STB_GLOBAL)
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
In arch/x86/kernel/kvm.c (ffffffff8107ff95)
Location: arch/x86/kernel/kvm.c:379
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
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
In arch/x86/kernel/kvm.c (ffffffff8108edd5)
Location: arch/x86/kernel/kvm.c:379
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
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
In arch/x86/kernel/kvm.c (ffffffff8109f995)
Location: arch/x86/kernel/kvm.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
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
In arch/x86/kernel/kvm.c (ffffffff810b72b5)
Location: arch/x86/kernel/kvm.c:395
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
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
In arch/x86/kernel/kvm.c (ffffffff810ba4a5)
Location: arch/x86/kernel/kvm.c:395
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
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
In arch/x86/kernel/kvm.c (ffffffff810c18e5)
Location: arch/x86/kernel/kvm.c:395
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
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
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076f90)
Location: arch/x86/kernel/kvm.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81076580-ffffffff8107659c: kvm_disable_steal_time.part.0 (STB_LOCAL)
ffffffff81076ee0-ffffffff81076efb: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066f9b)
Location: arch/x86/kernel/kvm.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81066bf0-ffffffff81066c1a: kvm_disable_steal_time.part.0 (STB_LOCAL)
ffffffff81067270-ffffffff8106728b: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076f40)
Location: arch/x86/kernel/kvm.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81076530-ffffffff8107654c: kvm_disable_steal_time.part.0 (STB_LOCAL)
ffffffff81076e90-ffffffff81076eab: kvm_disable_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kvm_disable_steal_time();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81078fb0)
Location: arch/x86/kernel/kvm.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
**Symbols:**

```
ffffffff81078700-ffffffff8107871c: kvm_disable_steal_time.part.0 (STB_LOCAL)
ffffffff81078f00-ffffffff81078f1b: kvm_disable_steal_time (STB_GLOBAL)
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
