# Function: <code>__wake_up_pollfree</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_pollfree(struct wait_queue_head *wq_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bb70)
Location: kernel/sched/wait.c:241
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_cleanup
```
**Symbols:**

```
ffffffff8111bb70-ffffffff8111bbab: __wake_up_pollfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_pollfree(struct wait_queue_head *wq_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113c350)
Location: kernel/sched/wait.c:240
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_cleanup
```
**Symbols:**

```
ffffffff8113c350-ffffffff8113c3ad: __wake_up_pollfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_pollfree(struct wait_queue_head *wq_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117b9e7)
Location: kernel/sched/wait.c:244
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
Direct callers:
  - fs/signalfd.c:signalfd_cleanup
```
**Symbols:**

```
ffffffff81166fc0-ffffffff8116701d: __wake_up_pollfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wake_up_pollfree(struct wait_queue_head *wq_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177390)
Location: kernel/sched/wait.c:244
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_cleanup
```
**Symbols:**

```
ffffffff81177390-ffffffff811773ed: __wake_up_pollfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wake_up_pollfree(struct wait_queue_head *wq_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c190)
Location: kernel/sched/wait.c:209
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_cleanup
```
**Symbols:**

```
ffffffff8118c190-ffffffff8118c203: __wake_up_pollfree (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
