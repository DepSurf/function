# Function: <code>cpuhp_down_callbacks</code>

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
int cpuhp_down_callbacks(unsigned int cpu, struct cpuhp_cpu_state *st, struct cpuhp_step *steps, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083c70)
Location: kernel/cpu.c:377
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff81083c70-ffffffff81083cfe: cpuhp_down_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpuhp_down_callbacks(unsigned int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81088c50)
Location: kernel/cpu.c:390
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff81088c50-ffffffff81088ccb: cpuhp_down_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpuhp_down_callbacks(unsigned int cpu, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085ac0)
Location: kernel/cpu.c:330
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff81085ac0-ffffffff81085b3b: cpuhp_down_callbacks (STB_LOCAL)
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
In kernel/cpu.c (ffffffff81988b83)
Location: kernel/cpu.c:836
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff819e54d0)
Location: kernel/cpu.c:921
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81a20700)
Location: kernel/cpu.c:936
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81a90c15)
Location: kernel/cpu.c:948
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81ac7f56)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81bc0a58)
Location: kernel/cpu.c:973
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81c39ae8)
Location: kernel/cpu.c:977
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81c2bfcd)
Location: kernel/cpu.c:1076
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81d4a765)
Location: kernel/cpu.c:1097
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81f19ddb)
Location: kernel/cpu.c:1103
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff820c1a4e)
Location: kernel/cpu.c:1129
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff82145719)
Location: kernel/cpu.c:1381
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff82227e39)
Location: kernel/cpu.c:1416
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffff800010d9bdac)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (c0e98444)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (c000000000141594)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81a66dc6)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81a23886)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81ad31d6)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81adf6d6)
Location: kernel/cpu.c:957
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
