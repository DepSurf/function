# Function: <code>out_of_line_wait_on_atomic_t</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int out_of_line_wait_on_atomic_t(atomic_t *p, int (*action)(atomic_t *), unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff81820aa0)
Location: kernel/sched/wait.c:559
Inline: False
```
**Symbols:**

```
ffffffff81820aa0-ffffffff81820b8a: out_of_line_wait_on_atomic_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int out_of_line_wait_on_atomic_t(atomic_t *p, int (*action)(atomic_t *), unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8189aef0)
Location: kernel/sched/wait.c:559
Inline: False
```
**Symbols:**

```
ffffffff8189aef0-ffffffff8189afda: out_of_line_wait_on_atomic_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int out_of_line_wait_on_atomic_t(atomic_t *p, int (*action)(atomic_t *), unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff818cf520)
Location: kernel/sched/wait.c:546
Inline: False
```
**Symbols:**

```
ffffffff818cf520-ffffffff818cf60a: out_of_line_wait_on_atomic_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int out_of_line_wait_on_atomic_t(atomic_t *p, int (*action)(atomic_t *), unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81906bb0)
Location: kernel/sched/wait_bit.c:213
Inline: False
```
**Symbols:**

```
ffffffff81906bb0-ffffffff81906cc1: out_of_line_wait_on_atomic_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int out_of_line_wait_on_atomic_t(atomic_t *p, wait_atomic_t_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81990c20)
Location: kernel/sched/wait_bit.c:213
Inline: False
```
**Symbols:**

```
ffffffff81990c20-ffffffff81990d36: out_of_line_wait_on_atomic_t (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*action)(atomic_t *)</code> ➡️ <code>wait_atomic_t_action_f *action</code>
</li>
</ul>
</details>
</li>
</ul>
