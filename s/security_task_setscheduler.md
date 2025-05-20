# Function: <code>security_task_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e6f0)
Location: security/security.c:972
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff8133e6f0-ffffffff8133e733: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373d00)
Location: security/security.c:996
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff81373d00-ffffffff81373d43: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a630)
Location: security/security.c:1017
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff8138a630-ffffffff8138a673: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139fb80)
Location: security/security.c:1660
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff8139fb80-ffffffff8139fbc3: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c57c0)
Location: security/security.c:1622
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff813c57c0-ffffffff813c5809: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f57d0)
Location: security/security.c:1126
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff813f57d0-ffffffff813f580a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410e00)
Location: security/security.c:1734
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff81410e00-ffffffff81410e3a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e610)
Location: security/security.c:1753
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff8143e610-ffffffff8143e651: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458040)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff81458040-ffffffff8145807a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaed0)
Location: security/security.c:1988
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff814aaed0-ffffffff814aaf0a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c84d0)
Location: security/security.c:2005
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff814c84d0-ffffffff814c850a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ceb10)
Location: security/security.c:2068
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff814ceb10-ffffffff814ceb4a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815277d0)
Location: security/security.c:2076
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff815277d0-ffffffff8152780a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc670)
Location: security/security.c:2082
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff815bc670-ffffffff815bc6bd: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816686d0)
Location: security/security.c:2134
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff816686d0-ffffffff8166871d: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0d20)
Location: security/security.c:3508
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_fork
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff816a0d20-ffffffff816a0d6d: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd6f0)
Location: security/security.c:3567
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_fork
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff816dd6f0-ffffffff816dd73d: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543df8)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffff800010543df8-ffff800010543e48: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9d44)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
c06f9d44-c06f9d98: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006985a0)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
c0000000006985a0-c000000000698648: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0134)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffe0003a0134-ffffffe0003a0170: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450620)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff81450620-ffffffff8145065a: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441070)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff81441070-ffffffff814410aa: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c6c0)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff8144c6c0-ffffffff8144c6fa: security_task_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463a90)
Location: security/security.c:1792
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - fs/proc/base.c:timerslack_ns_write
```
**Symbols:**

```
ffffffff81463a90-ffffffff81463aca: security_task_setscheduler (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
