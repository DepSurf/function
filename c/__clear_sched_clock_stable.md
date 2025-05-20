# Function: <code>__clear_sched_clock_stable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __clear_sched_clock_stable(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b11d0)
Location: kernel/sched/clock.c:106
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810b11d0-ffffffff810b11e8: __clear_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __clear_sched_clock_stable(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b3c80)
Location: kernel/sched/clock.c:109
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810b3c80-ffffffff810b3c98: __clear_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __clear_sched_clock_stable(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ba2c0)
Location: kernel/sched/clock.c:109
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810ba2c0-ffffffff810ba2d8: __clear_sched_clock_stable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b4d68)
Location: kernel/sched/clock.c:195
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810bc06f)
Location: kernel/sched/clock.c:195
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810c36ff)
Location: kernel/sched/clock.c:183
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810cc9e7)
Location: kernel/sched/clock.c:179
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810d4dd7)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810df397)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810e7687)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810e52c7)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810e7277)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810fe8a7)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/build_utility.c (ffffffff81145313)
Location: kernel/sched/clock.c:178
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:clear_sched_clock_stable
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
In kernel/sched/build_utility.c (ffffffff811723e3)
Location: kernel/sched/clock.c:178
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:clear_sched_clock_stable
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
In kernel/sched/build_utility.c (ffffffff81182bf3)
Location: kernel/sched/clock.c:178
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:clear_sched_clock_stable
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
In kernel/sched/build_utility.c (ffffffff81191478)
Location: kernel/sched/clock.c:178
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810d9587)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810c7f67)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810d58c7)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
In kernel/sched/clock.c (ffffffff810e11b7)
Location: kernel/sched/clock.c:180
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
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
</ul>
