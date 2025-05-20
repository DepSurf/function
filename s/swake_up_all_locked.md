# Function: <code>swake_up_all_locked</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ff750)
Location: kernel/sched/swait.c:42
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
```
**Symbols:**

```
ffffffff810ff750-ffffffff810ff7ad: swake_up_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810fe260)
Location: kernel/sched/swait.c:42
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
```
**Symbols:**

```
ffffffff810fe260-ffffffff810fe2bd: swake_up_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff81100640)
Location: kernel/sched/swait.c:42
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
```
**Symbols:**

```
ffffffff81100640-ffffffff8110069d: swake_up_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff8111c6a0)
Location: kernel/sched/swait.c:42
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
```
**Symbols:**

```
ffffffff8111c6a0-ffffffff8111c6fd: swake_up_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81140d61)
Location: kernel/sched/swait.c:41
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:complete_all
```
**Symbols:**

```
ffffffff81148b70-ffffffff81148bd7: swake_up_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116bbe1)
Location: kernel/sched/swait.c:41
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:complete_all
```
**Symbols:**

```
ffffffff811773b0-ffffffff81177417: swake_up_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117c661)
Location: kernel/sched/swait.c:41
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:complete_all
```
**Symbols:**

```
ffffffff81188000-ffffffff81188067: swake_up_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void swake_up_all_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a461)
Location: kernel/sched/swait.c:41
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:complete_all
```
**Symbols:**

```
ffffffff81196850-ffffffff811968c0: swake_up_all_locked (STB_GLOBAL)
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
