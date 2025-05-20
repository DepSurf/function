# Function: <code>mce_start_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mce_start_timer(unsigned int cpu, struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043ca0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1642
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
```
**Symbols:**

```
ffffffff81043ca0-ffffffff81043d04: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mce_start_timer(unsigned int cpu, struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043dd0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1720
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff81043dd0-ffffffff81043e34: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045890)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1777
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff81045890-ffffffff810458c2: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810459d0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1752
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff810459d0-ffffffff81045a03: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049ed0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1761
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff81049ed0-ffffffff81049f03: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c500)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff8104c500-ffffffff8104c532: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049bf0)
Location: arch/x86/kernel/cpu/mce/core.c:1778
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff81049bf0-ffffffff81049c22: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cd80)
Location: arch/x86/kernel/cpu/mce/core.c:1800
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff8104cd80-ffffffff8104cdb2: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d720)
Location: arch/x86/kernel/cpu/mce/core.c:1800
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff8104d720-ffffffff8104d752: mce_start_timer (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810530aa)
Location: arch/x86/kernel/cpu/mce/core.c:1854
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810521fa)
Location: arch/x86/kernel/cpu/mce/core.c:1927
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810539c0)
Location: arch/x86/kernel/cpu/mce/core.c:1939
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c2bf)
Location: arch/x86/kernel/cpu/mce/core.c:2002
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81068796)
Location: arch/x86/kernel/cpu/mce/core.c:2039
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078299)
Location: arch/x86/kernel/cpu/mce/core.c:2039
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a549)
Location: arch/x86/kernel/cpu/mce/core.c:2055
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081a79)
Location: arch/x86/kernel/cpu/mce/core.c:2084
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
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
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d880)
Location: arch/x86/kernel/cpu/mce/core.c:1800
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff8104d880-ffffffff8104d8b2: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c050)
Location: arch/x86/kernel/cpu/mce/core.c:1800
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff8103c050-ffffffff8103c082: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d6d0)
Location: arch/x86/kernel/cpu/mce/core.c:1800
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff8104d6d0-ffffffff8104d702: mce_start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mce_start_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104eb10)
Location: arch/x86/kernel/cpu/mce/core.c:1800
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
```
**Symbols:**

```
ffffffff8104eb10-ffffffff8104eb42: mce_start_timer (STB_LOCAL)
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
<b>Param removed. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, t</code> ➡️ <code>t</code>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
