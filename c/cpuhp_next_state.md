# Function: <code>cpuhp_next_state</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpuhp_next_state(bool bringup, enum cpuhp_state *state_to_run, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4ff0)
Location: kernel/cpu.c:621
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810a4ff0-ffffffff810a504b: cpuhp_next_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cpuhp_next_state(bool bringup, enum cpuhp_state *state_to_run, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b6830)
Location: kernel/cpu.c:638
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810b6830-ffffffff810b688b: cpuhp_next_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cpuhp_next_state(bool bringup, enum cpuhp_state *state_to_run, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ccd90)
Location: kernel/cpu.c:641
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
```
**Symbols:**

```
ffffffff810ccd90-ffffffff810cce09: cpuhp_next_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cpuhp_next_state(bool bringup, enum cpuhp_state *state_to_run, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ead70)
Location: kernel/cpu.c:641
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:__cpuhp_invoke_callback_range
```
**Symbols:**

```
ffffffff810ead70-ffffffff810eade9: cpuhp_next_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpuhp_next_state(bool bringup, enum cpuhp_state *state_to_run, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f69b0)
Location: kernel/cpu.c:891
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:__cpuhp_invoke_callback_range
```
**Symbols:**

```
ffffffff810f69b0-ffffffff810f6a29: cpuhp_next_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpuhp_next_state(bool bringup, enum cpuhp_state *state_to_run, struct cpuhp_cpu_state *st, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ffd60)
Location: kernel/cpu.c:919
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:__cpuhp_invoke_callback_range
```
**Symbols:**

```
ffffffff810ffd60-ffffffff810ffdd9: cpuhp_next_state (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
