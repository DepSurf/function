# Function: <code>cpuhp_kick_ap</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bb60)
Location: kernel/cpu.c:401
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8108bb60-ffffffff8108bbd8: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108f420)
Location: kernel/cpu.c:477
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8108f420-ffffffff8108f496: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81097720)
Location: kernel/cpu.c:484
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff81097720-ffffffff81097796: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bc90)
Location: kernel/cpu.c:494
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8109bc90-ffffffff8109bd11: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a2210)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810a2210-ffffffff810a2291: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a97b0)
Location: kernel/cpu.c:505
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_wait_for_ap
```
**Symbols:**

```
ffffffff810a97b0-ffffffff810a988c: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a51e0)
Location: kernel/cpu.c:505
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_wait_for_ap
```
**Symbols:**

```
ffffffff810a51e0-ffffffff810a52bc: cpuhp_kick_ap (STB_LOCAL)
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
In kernel/cpu.c (ffffffff810a5f34)
Location: kernel/cpu.c:532
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810b79bf)
Location: kernel/cpu.c:543
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpuhp_kick_ap(int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cde10)
Location: kernel/cpu.c:545
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810cde10-ffffffff810cded1: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpuhp_kick_ap(int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ec000)
Location: kernel/cpu.c:545
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810ec000-ffffffff810ec0c1: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpuhp_kick_ap(int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f7ce0)
Location: kernel/cpu.c:739
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_bringup_ap
```
**Symbols:**

```
ffffffff810f7ce0-ffffffff810f7d9c: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpuhp_kick_ap(int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff811011b0)
Location: kernel/cpu.c:767
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_bringup_ap
```
**Symbols:**

```
ffffffff811011b0-ffffffff8110126c: cpuhp_kick_ap (STB_LOCAL)
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
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f71c8)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffff8000100f71c8-ffff8000100f7268: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0355660)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
c0355660-c03556fc: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013d7b0)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
c00000000013d7b0-c00000000013d88c: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c2d60)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffe0000c2d60-ffffffe0000c2dee: cpuhp_kick_ap (STB_LOCAL)
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
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bb30)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8109bb30-ffffffff8109bbb1: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108a560)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8108a560-ffffffff8108a5e1: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bae0)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff8109bae0-ffffffff8109bb61: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpuhp_kick_ap(struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3750)
Location: kernel/cpu.c:504
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810a3750-ffffffff810a37d1: cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
