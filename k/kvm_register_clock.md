# Function: <code>kvm_register_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kvm_register_clock(char *txt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810643c0)
Location: arch/x86/kernel/kvmclock.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810643c0-ffffffff8106443d: kvm_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kvm_register_clock(char *txt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81064030)
Location: arch/x86/kernel/kvmclock.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81064030-ffffffff810640dd: kvm_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kvm_register_clock(char *txt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81067530)
Location: arch/x86/kernel/kvmclock.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81067530-ffffffff810675dd: kvm_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kvm_register_clock(char *txt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81066800)
Location: arch/x86/kernel/kvmclock.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81066800-ffffffff810668ad: kvm_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kvm_register_clock(char *txt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8106a9d0)
Location: arch/x86/kernel/kvmclock.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff8106a9d0-ffffffff8106aa7d: kvm_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kvm_register_clock(char *txt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8106d6b0)
Location: arch/x86/kernel/kvmclock.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff8106d6b0-ffffffff8106d75f: kvm_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81073740)
Location: arch/x86/kernel/kvmclock.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81073740-ffffffff81073794: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810772c0)
Location: arch/x86/kernel/kvmclock.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff810772c0-ffffffff81077313: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81078350)
Location: arch/x86/kernel/kvmclock.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81078350-ffffffff810783a3: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f880)
Location: arch/x86/kernel/kvmclock.c:178
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8107f680-ffffffff8107f6d9: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f4e0)
Location: arch/x86/kernel/kvmclock.c:177
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8107f2e0-ffffffff8107f339: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810805c0)
Location: arch/x86/kernel/kvmclock.c:176
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81080440-ffffffff8108049a: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8108f4f0)
Location: arch/x86/kernel/kvmclock.c:167
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8108f370-ffffffff8108f3ca: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810a00a0)
Location: arch/x86/kernel/kvmclock.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff810a00a0-ffffffff810a015a: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810b7af0)
Location: arch/x86/kernel/kvmclock.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff810b7af0-ffffffff810b7baa: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810bace0)
Location: arch/x86/kernel/kvmclock.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff810bace0-ffffffff810bad9a: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810c2120)
Location: arch/x86/kernel/kvmclock.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff810c2120-ffffffff810c21da: kvm_register_clock (STB_LOCAL)
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
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81077350)
Location: arch/x86/kernel/kvmclock.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81077350-ffffffff810773a3: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81067450)
Location: arch/x86/kernel/kvmclock.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81067450-ffffffff810674a9: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81077300)
Location: arch/x86/kernel/kvmclock.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81077300-ffffffff81077353: kvm_register_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kvm_register_clock(char *txt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81079390)
Location: arch/x86/kernel/kvmclock.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
**Symbols:**

```
ffffffff81079390-ffffffff810793e3: kvm_register_clock (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
