# Function: <code>kvm_para_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063d80)
Location: arch/x86/kernel/kvm.c:540
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81063d80-ffffffff81063dac: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81f9cd6d)
Location: arch/x86/kernel/kvm.c:531
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810639a0-ffffffff810639cc: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81fd82c0)
Location: arch/x86/kernel/kvm.c:517
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81066e50-ffffffff81066e7c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff820b910b)
Location: arch/x86/kernel/kvm.c:524
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81066120-ffffffff8106614c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106a1b0)
Location: arch/x86/kernel/kvm.c:565
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8106a1b0-ffffffff8106a1dc: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff826e984b)
Location: arch/x86/kernel/kvm.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8106ccb0-ffffffff8106ccdc: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828a0499)
Location: arch/x86/kernel/kvm.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81072dc0-ffffffff81072dec: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810766f0)
Location: arch/x86/kernel/kvm.c:693
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810766f0-ffffffff8107671c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81077700)
Location: arch/x86/kernel/kvm.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff81077700-ffffffff8107772c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82ce2fc9)
Location: arch/x86/kernel/kvm.c:696
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff8107ea60-ffffffff8107ea8c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82fd02bb)
Location: arch/x86/kernel/kvm.c:713
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff8107e690-ffffffff8107e6bc: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff831dacce)
Location: arch/x86/kernel/kvm.c:773
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff8107f700-ffffffff8107f72c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff832bdf23)
Location: arch/x86/kernel/kvm.c:776
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff8108e4c0-ffffffff8108e4ec: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8346faca)
Location: arch/x86/kernel/kvm.c:897
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff8109f330-ffffffff8109f364: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff83e96315)
Location: arch/x86/kernel/kvm.c:890
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff810b6980-ffffffff810b69b4: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff836b9e95)
Location: arch/x86/kernel/kvm.c:890
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff810b9ac0-ffffffff810b9af4: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff838ea7c5)
Location: arch/x86/kernel/kvm.c:891
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff810c1160-ffffffff810c1194: kvm_para_available (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int kvm_para_available();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/kvm.c (c0000000000751f4)
Location: arch/powerpc/include/asm/kvm_para.h:17
Inline: False
Direct callers:
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
```
```
In drivers/cpuidle/governors/haltpoll.c (c0000000013b8be0)
Location: arch/powerpc/include/asm/kvm_para.h:17
Inline: True
Inline callers:
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
c0000000000751f4-c000000000075258: kvm_para_available (STB_LOCAL)
```
</details>
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
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076700)
Location: arch/x86/kernel/kvm.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff81076700-ffffffff8107672c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066670)
Location: arch/x86/kernel/kvm.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff81066670-ffffffff8106669c: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810766b0)
Location: arch/x86/kernel/kvm.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff810766b0-ffffffff810766dc: kvm_para_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kvm_para_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81078880)
Location: arch/x86/kernel/kvm.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
**Symbols:**

```
ffffffff81078880-ffffffff810788ac: kvm_para_available (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
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
