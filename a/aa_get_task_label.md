# Function: <code>aa_get_task_label</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/context.c (ffffffff81377320)
Location: security/apparmor/context.c:77
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81377320-ffffffff81377468: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/context.c (ffffffff813afe90)
Location: security/apparmor/context.c:77
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff813afe90-ffffffff813affc3: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/context.c (ffffffff813c7010)
Location: security/apparmor/context.c:77
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff813c7010-ffffffff813c7143: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/context.c (ffffffff813dcc30)
Location: security/apparmor/context.c:65
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff813dcc30-ffffffff813dcc87: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/context.c (ffffffff814036b0)
Location: security/apparmor/context.c:65
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814036b0-ffffffff8140374e: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81434770)
Location: security/apparmor/task.c:28
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81434770-ffffffff8143480a: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff814512c0)
Location: security/apparmor/task.c:28
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814512c0-ffffffff81451365: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff8147ed70)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8147ed70-ffffffff8147ede4: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81498a70)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81498a70-ffffffff81498ae4: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff814f0e70)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814f0e70-ffffffff814f0f26: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff8150e0f0)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8150e0f0-ffffffff8150e1bd: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81514b10)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81514b10-ffffffff81514bd9: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81572ac0)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81572ac0-ffffffff81572b89: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff8160fd40)
Location: security/apparmor/task.c:29
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8160fd40-ffffffff8160fe38: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816c2760)
Location: security/apparmor/task.c:29
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
```
**Symbols:**

```
ffffffff816c2760-ffffffff816c2858: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816fb310)
Location: security/apparmor/task.c:29
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
```
**Symbols:**

```
ffffffff816fb310-ffffffff816fb404: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff817382c0)
Location: security/apparmor/task.c:29
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_getlsmblob_obj
```
**Symbols:**

```
ffffffff817382c0-ffffffff817383b7: aa_get_task_label (STB_GLOBAL)
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
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffff80001058e698)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffff80001058e698-ffff80001058e718: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (c073f50c)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
c073f50c-c073f588: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (c0000000007012e0)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
c0000000007012e0-c00000000070137c: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffe0003dc5e4)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffe0003dc5e4-ffffffe0003dc658: aa_get_task_label (STB_GLOBAL)
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
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81491050)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81491050-ffffffff814910c4: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81481a70)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81481a70-ffffffff81481ae4: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff8148d0f0)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8148d0f0-ffffffff8148d164: aa_get_task_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *aa_get_task_label(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff814a4f60)
Location: security/apparmor/task.c:24
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814a4f60-ffffffff814a4fff: aa_get_task_label (STB_GLOBAL)
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
