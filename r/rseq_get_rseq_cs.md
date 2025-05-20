# Function: <code>rseq_get_rseq_cs</code>

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
In kernel/rseq.c (ffffffff811ea2ef)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (ffffffff811fae5f)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (ffffffff81212550)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (ffffffff8121fd30)
Location: kernel/rseq.c:115
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rseq_get_rseq_cs(struct task_struct *t, struct rseq_cs *rseq_cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:115
Inline: False
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff8124bdd0-ffffffff8124c07c: rseq_get_rseq_cs (STB_LOCAL)
ffffffff8124c527-ffffffff8124c550: rseq_get_rseq_cs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rseq_get_rseq_cs(struct task_struct *t, struct rseq_cs *rseq_cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:115
Inline: False
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff81256260-ffffffff8125650c: rseq_get_rseq_cs (STB_LOCAL)
ffffffff81be6943-ffffffff81be696c: rseq_get_rseq_cs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rseq_get_rseq_cs(struct task_struct *t, struct rseq_cs *rseq_cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:122
Inline: False
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff8125a830-ffffffff8125aa50: rseq_get_rseq_cs (STB_LOCAL)
ffffffff81bd8644-ffffffff81bd866d: rseq_get_rseq_cs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:122
Inline: True
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff81296620-ffffffff81296839: rseq_get_rseq_cs.isra.0 (STB_LOCAL)
ffffffff81cb9c68-ffffffff81cb9c91: rseq_get_rseq_cs.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:122
Inline: True
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff812ec5f0-ffffffff812ec86c: rseq_get_rseq_cs.isra.0 (STB_LOCAL)
ffffffff81e6b266-ffffffff81e6b288: rseq_get_rseq_cs.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (ffffffff81356930)
Location: kernel/rseq.c:123
Inline: True
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff81356930-ffffffff81356b9a: rseq_get_rseq_cs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rseq_get_rseq_cs(struct task_struct *t, struct rseq_cs *rseq_cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff813883f0)
Location: kernel/rseq.c:152
Inline: False
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff813883f0-ffffffff81388661: rseq_get_rseq_cs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rseq_get_rseq_cs(struct task_struct *t, struct rseq_cs *rseq_cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff813b1e50)
Location: kernel/rseq.c:152
Inline: False
Direct callers:
  - kernel/rseq.c:rseq_ip_fixup
```
**Symbols:**

```
ffffffff813b1e50-ffffffff813b20c1: rseq_get_rseq_cs (STB_LOCAL)
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
In kernel/rseq.c (ffff8000102ac778)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (c04d9554)
Location: kernel/rseq.c:115
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
In kernel/rseq.c (c0000000003607f4)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (ffffffff81218380)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (ffffffff8120b590)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (ffffffff81216120)
Location: kernel/rseq.c:115
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
In kernel/rseq.c (ffffffff81224dd2)
Location: kernel/rseq.c:115
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
