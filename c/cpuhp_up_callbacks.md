# Function: <code>cpuhp_up_callbacks</code>

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
int cpuhp_up_callbacks(unsigned int cpu, struct cpuhp_cpu_state *st, struct cpuhp_step *steps, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083d00)
Location: kernel/cpu.c:407
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff81083d00-ffffffff81083dab: cpuhp_up_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpuhp_up_callbacks(unsigned int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81088cd0)
Location: kernel/cpu.c:417
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff81088cd0-ffffffff81088d86: cpuhp_up_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpuhp_up_callbacks(unsigned int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085b40)
Location: kernel/cpu.c:357
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff81085b40-ffffffff81085bf6: cpuhp_up_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c90a)
Location: kernel/cpu.c:469
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810902a6)
Location: kernel/cpu.c:555
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff81099056)
Location: kernel/cpu.c:572
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff8109d5e2)
Location: kernel/cpu.c:582
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810a3b32)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810aab85)
Location: kernel/cpu.c:607
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810a6415)
Location: kernel/cpu.c:607
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810a73c4)
Location: kernel/cpu.c:677
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810b8dc1)
Location: kernel/cpu.c:694
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810cf70f)
Location: kernel/cpu.c:697
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810edaf2)
Location: kernel/cpu.c:727
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff810f9bdd)
Location: kernel/cpu.c:977
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff81102fed)
Location: kernel/cpu.c:1005
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f94b0)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c035779c)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001402b4)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3ed4)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_up
```
</details>
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
In kernel/cpu.c (ffffffff8109d452)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff8108be72)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
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
In kernel/cpu.c (ffffffff8109d402)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5282)
Location: kernel/cpu.c:591
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct cpuhp_step *steps</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, st, steps, target</code> ➡️ <code>cpu, st, target</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
