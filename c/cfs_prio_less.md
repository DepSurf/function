# Function: <code>cfs_prio_less</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool cfs_prio_less(struct task_struct *a, struct task_struct *b, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11117
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81ca67b6-ffffffff81ca67db: cfs_prio_less.cold (STB_LOCAL)
ffffffff81110b30-ffffffff81110d5b: cfs_prio_less (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool cfs_prio_less(struct task_struct *a, struct task_struct *b, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11235
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81e55fea-ffffffff81e5600f: cfs_prio_less.cold (STB_LOCAL)
ffffffff8112cd40-ffffffff8112cf56: cfs_prio_less (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool cfs_prio_less(struct task_struct *a, struct task_struct *b, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11762
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff8205720e-ffffffff82057233: cfs_prio_less.cold (STB_LOCAL)
ffffffff81156a70-ffffffff81156c86: cfs_prio_less (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool cfs_prio_less(const struct task_struct *a, const struct task_struct *b, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12067
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff820d5a38-ffffffff820d5a5d: cfs_prio_less.cold (STB_LOCAL)
ffffffff81166b00-ffffffff81166d48: cfs_prio_less (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool cfs_prio_less(const struct task_struct *a, const struct task_struct *b, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12545
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff821b0ab0-ffffffff821b0ad5: cfs_prio_less.cold (STB_LOCAL)
ffffffff81173850-ffffffff81173ac8: cfs_prio_less (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct task_struct *a</code> ➡️ <code>const struct task_struct *a</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct task_struct *b</code> ➡️ <code>const struct task_struct *b</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
