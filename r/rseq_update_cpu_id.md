# Function: <code>rseq_update_cpu_id</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff811ea4cb)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff811fb03b)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff8121274e)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff8121ff2e)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rseq_update_cpu_id(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff8124c080)
Location: kernel/rseq.c:84
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff8124c080-ffffffff8124c11f: rseq_update_cpu_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rseq_update_cpu_id(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81256510)
Location: kernel/rseq.c:84
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff81256510-ffffffff81256594: rseq_update_cpu_id (STB_LOCAL)
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
In kernel/rseq.c (ffffffff8125adcc)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff81296bc1)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rseq_update_cpu_id(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff812eca40)
Location: kernel/rseq.c:84
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff812eca40-ffffffff812ecafe: rseq_update_cpu_id (STB_LOCAL)
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
In kernel/rseq.c (ffffffff81356fb1)
Location: kernel/rseq.c:85
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffff8000102ac860)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (c04d9a38)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (c000000000360ac0)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff8121857e)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff8120b78e)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff8121631e)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
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
In kernel/rseq.c (ffffffff812254fc)
Location: kernel/rseq.c:84
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
