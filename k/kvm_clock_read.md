# Function: <code>kvm_clock_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
cycle_t kvm_clock_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81064230)
Location: arch/x86/kernel/kvmclock.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81064230-ffffffff81064250: kvm_clock_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
cycle_t kvm_clock_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81f9d01c)
Location: arch/x86/kernel/kvmclock.c:82
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff81063e30-ffffffff81063e50: kvm_clock_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 kvm_clock_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81fd85ab)
Location: arch/x86/kernel/kvmclock.c:82
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff81067330-ffffffff81067350: kvm_clock_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 kvm_clock_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff820b93c4)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff81066620-ffffffff81066640: kvm_clock_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 kvm_clock_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff826bfd32)
Location: arch/x86/kernel/kvmclock.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff8106a7e0-ffffffff8106a800: kvm_clock_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 kvm_clock_read();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff826e9c39)
Location: arch/x86/kernel/kvmclock.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff8106d4a0-ffffffff8106d4c0: kvm_clock_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff828a08ab)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff828b8a91)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff828bef7f)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff82ce326f)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
In arch/x86/kernel/kvmclock.c (ffffffff82fd0568)
Location: arch/x86/kernel/kvmclock.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
In arch/x86/kernel/kvmclock.c (ffffffff831db1fb)
Location: arch/x86/kernel/kvmclock.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
In arch/x86/kernel/kvmclock.c (ffffffff832be570)
Location: arch/x86/kernel/kvmclock.c:74
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
In arch/x86/kernel/kvmclock.c (ffffffff83470284)
Location: arch/x86/kernel/kvmclock.c:74
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
In arch/x86/kernel/kvmclock.c (ffffffff83e96d35)
Location: arch/x86/kernel/kvmclock.c:74
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
In arch/x86/kernel/kvmclock.c (ffffffff836ba8e5)
Location: arch/x86/kernel/kvmclock.c:74
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
In arch/x86/kernel/kvmclock.c (ffffffff838eb2ea)
Location: arch/x86/kernel/kvmclock.c:74
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff828a9f55)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff828a2236)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff828bce54)
Location: arch/x86/kernel/kvmclock.c:85
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 kvm_clock_read();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81079330)
Location: arch/x86/kernel/kvmclock.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
```
**Symbols:**

```
ffffffff81079330-ffffffff8107935a: kvm_clock_read (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>cycle_t</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
