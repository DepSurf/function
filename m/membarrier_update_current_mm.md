# Function: <code>membarrier_update_current_mm</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct *next_mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81109360)
Location: kernel/sched/membarrier.c:232
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
**Symbols:**

```
ffffffff81109360-ffffffff81109394: membarrier_update_current_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct *next_mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110b200)
Location: kernel/sched/membarrier.c:232
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
**Symbols:**

```
ffffffff8110b200-ffffffff8110b234: membarrier_update_current_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct *next_mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81129a60)
Location: kernel/sched/membarrier.c:233
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
**Symbols:**

```
ffffffff81129a60-ffffffff81129a94: membarrier_update_current_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct *next_mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114cd30)
Location: kernel/sched/membarrier.c:232
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
**Symbols:**

```
ffffffff8114cd30-ffffffff8114cd70: membarrier_update_current_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct *next_mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117bd60)
Location: kernel/sched/membarrier.c:232
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
**Symbols:**

```
ffffffff8117bd60-ffffffff8117bda0: membarrier_update_current_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct *next_mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118ca10)
Location: kernel/sched/membarrier.c:233
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
**Symbols:**

```
ffffffff8118ca10-ffffffff8118ca53: membarrier_update_current_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct *next_mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119b3c0)
Location: kernel/sched/membarrier.c:236
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
**Symbols:**

```
ffffffff8119b3c0-ffffffff8119b403: membarrier_update_current_mm (STB_GLOBAL)
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
