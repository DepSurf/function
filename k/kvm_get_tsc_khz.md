# Function: <code>kvm_get_tsc_khz</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81064350)
Location: arch/x86/kernel/kvmclock.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81064350-ffffffff81064370: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81f9d0c2)
Location: arch/x86/kernel/kvmclock.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81063ea0-ffffffff81063ec0: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81fd8651)
Location: arch/x86/kernel/kvmclock.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810673a0-ffffffff810673c0: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff820b9461)
Location: arch/x86/kernel/kvmclock.c:136
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81066690-ffffffff810666b0: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff826bfdcf)
Location: arch/x86/kernel/kvmclock.c:131
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8106a850-ffffffff8106a870: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8106d510)
Location: arch/x86/kernel/kvmclock.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8106d510-ffffffff8106d540: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810737e0)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810737e0-ffffffff81073803: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81077360)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81077360-ffffffff81077383: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810783f0)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810783f0-ffffffff81078413: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f720)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8107f720-ffffffff8107f743: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f380)
Location: arch/x86/kernel/kvmclock.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8107f380-ffffffff8107f3a3: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810804a0)
Location: arch/x86/kernel/kvmclock.c:126
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810804a0-ffffffff810804c3: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8108f3d0)
Location: arch/x86/kernel/kvmclock.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8108f3d0-ffffffff8108f3f3: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810a0070)
Location: arch/x86/kernel/kvmclock.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810a0070-ffffffff810a0099: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810b7ab0)
Location: arch/x86/kernel/kvmclock.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810b7ab0-ffffffff810b7ad9: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810baca0)
Location: arch/x86/kernel/kvmclock.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810baca0-ffffffff810bacc9: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810c20e0)
Location: arch/x86/kernel/kvmclock.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810c20e0-ffffffff810c2109: kvm_get_tsc_khz (STB_LOCAL)
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
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810773f0)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810773f0-ffffffff81077413: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810673f0)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810673f0-ffffffff81067413: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810773a0)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810773a0-ffffffff810773c3: kvm_get_tsc_khz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int kvm_get_tsc_khz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81079430)
Location: arch/x86/kernel/kvmclock.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81079430-ffffffff81079453: kvm_get_tsc_khz (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
