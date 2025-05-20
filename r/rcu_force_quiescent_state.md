# Function: <code>rcu_force_quiescent_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:509
Inline: False
```
**Symbols:**

```
ffffffff810ea8a0-ffffffff810ea8b0: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:510
Inline: False
```
**Symbols:**

```
ffffffff810f17a0-ffffffff810f17b0: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f25f0)
Location: kernel/rcu/tree.c:628
Inline: False
```
**Symbols:**

```
ffffffff810f25f0-ffffffff810f2607: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc380)
Location: kernel/rcu/tree.c:625
Inline: False
```
**Symbols:**

```
ffffffff810fc380-ffffffff810fc397: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81105fd0)
Location: kernel/rcu/tree.c:610
Inline: False
```
**Symbols:**

```
ffffffff81105fd0-ffffffff81105fe7: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111a50)
Location: kernel/rcu/tree.c:509
Inline: False
```
**Symbols:**

```
ffffffff81111a50-ffffffff81111a60: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111b1d0)
Location: kernel/rcu/tree.c:2243
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff8111b1d0-ffffffff8111b293: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811275c0)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff811275c0-ffffffff81127683: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135520)
Location: kernel/rcu/tree.c:2568
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81135520-ffffffff811355ea: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81130ce0)
Location: kernel/rcu/tree.c:2694
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81130ce0-ffffffff81130daa: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811313a0)
Location: kernel/rcu/tree.c:2713
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff811313a0-ffffffff8113146a: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81153280)
Location: kernel/rcu/tree.c:2664
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81153280-ffffffff8115334a: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81179220)
Location: kernel/rcu/tree.c:2741
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff81179220-ffffffff81179317: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b0950)
Location: kernel/rcu/tree.c:2409
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff811b0950-ffffffff811b0a47: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c2920)
Location: kernel/rcu/tree.c:2302
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff811c2920-ffffffff811c2a17: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d48d0)
Location: kernel/rcu/tree.c:2366
Inline: True
Direct callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:__call_rcu_common
```
**Symbols:**

```
ffffffff811d48d0-ffffffff811d49e1: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018ece0)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffff80001018ece0-ffff80001018ee78: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03db668)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
c03db668-c03db76c: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e8060)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
c0000000001e8060-c0000000001e8250: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000122194)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffe000122194-ffffffe0001222d8: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111fba0)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff8111fba0-ffffffff8111fc63: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111630)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff81111630-ffffffff811116f3: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111da90)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff8111da90-ffffffff8111db53: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_force_quiescent_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811294b0)
Location: kernel/rcu/tree.c:2305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff811294b0-ffffffff81129592: rcu_force_quiescent_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
