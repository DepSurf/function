# Function: <code>task_is_descendant</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813950c0)
Location: security/yama/yama_lsm.c:210
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff813950c0-ffffffff81395115: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813d1147)
Location: security/yama/yama_lsm.c:281
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff813d0c40-ffffffff813d0c95: task_is_descendant.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813e885a)
Location: security/yama/yama_lsm.c:281
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff813e8340-ffffffff813e8395: task_is_descendant.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813f4850)
Location: security/yama/yama_lsm.c:281
Inline: True
```
**Symbols:**

```
ffffffff813f4850-ffffffff813f48aa: task_is_descendant.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8141c900)
Location: security/yama/yama_lsm.c:281
Inline: True
```
**Symbols:**

```
ffffffff8141c900-ffffffff8141c95a: task_is_descendant.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8144ea00)
Location: security/yama/yama_lsm.c:276
Inline: True
```
**Symbols:**

```
ffffffff8144ea00-ffffffff8144ea5a: task_is_descendant.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8146b9d0)
Location: security/yama/yama_lsm.c:276
Inline: True
```
**Symbols:**

```
ffffffff8146b9d0-ffffffff8146ba2a: task_is_descendant.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814989c0)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff814989c0-ffffffff81498a1a: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814b28f0)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff814b28f0-ffffffff814b294a: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81511b30)
Location: security/yama/yama_lsm.c:272
Inline: True
Direct callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
```
**Symbols:**

```
ffffffff81511b30-ffffffff81511b9a: task_is_descendant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8152e960)
Location: security/yama/yama_lsm.c:272
Inline: True
Direct callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
```
**Symbols:**

```
ffffffff8152e960-ffffffff8152e9e2: task_is_descendant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81534c50)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff81534c50-ffffffff81534cd2: task_is_descendant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff815931c0)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff815931c0-ffffffff81593242: task_is_descendant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81635280)
Location: security/yama/yama_lsm.c:272
Inline: True
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff81635280-ffffffff8163531e: task_is_descendant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff816ebee0)
Location: security/yama/yama_lsm.c:273
Inline: True
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff816ebee0-ffffffff816ebf7e: task_is_descendant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81726310)
Location: security/yama/yama_lsm.c:273
Inline: True
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff81726310-ffffffff817263ae: task_is_descendant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int task_is_descendant(struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81767530)
Location: security/yama/yama_lsm.c:273
Inline: True
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff81767530-ffffffff817675ce: task_is_descendant (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffff8000105aa2d8)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffff8000105aa2d8-ffff8000105aa354: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (c075a190)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
c075a190-c075a1f4: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (c000000000727ac0)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
c000000000727ac0-c000000000727b28: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffe0003f34e2)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffe0003f34e2-ffffffe0003f354c: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814aaed0)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff814aaed0-ffffffff814aaf2a: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8149b8f0)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff8149b8f0-ffffffff8149b94a: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814a6f70)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff814a6f70-ffffffff814a6fca: task_is_descendant.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814bfa10)
Location: security/yama/yama_lsm.c:272
Inline: True
```
**Symbols:**

```
ffffffff814bfa10-ffffffff814bfa91: task_is_descendant.part.0 (STB_LOCAL)
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
