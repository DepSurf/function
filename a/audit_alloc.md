# Function: <code>audit_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811281c0)
Location: kernel/auditsc.c:920
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811281c0-ffffffff81128335: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81130370)
Location: kernel/auditsc.c:925
Inline: False
```
**Symbols:**

```
ffffffff81130370-ffffffff811304dc: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113a0e0)
Location: kernel/auditsc.c:930
Inline: False
```
**Symbols:**

```
ffffffff8113a0e0-ffffffff8113a244: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b720)
Location: kernel/auditsc.c:931
Inline: False
```
**Symbols:**

```
ffffffff8113b720-ffffffff8113b884: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81148480)
Location: kernel/auditsc.c:931
Inline: False
```
**Symbols:**

```
ffffffff81148480-ffffffff811485e3: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81156e50)
Location: kernel/auditsc.c:938
Inline: False
```
**Symbols:**

```
ffffffff81156e50-ffffffff81156fb3: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81163ea0)
Location: kernel/auditsc.c:894
Inline: False
```
**Symbols:**

```
ffffffff81163ea0-ffffffff81164003: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170ab0)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81170ab0-ffffffff81170c09: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117c930)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8117c930-ffffffff8117ca89: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f530)
Location: kernel/auditsc.c:927
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8118f530-ffffffff8118f6b8: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118c7a0)
Location: kernel/auditsc.c:945
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8118c7a0-ffffffff8118c94a: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d4d0)
Location: kernel/auditsc.c:944
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8118d4d0-ffffffff8118d67a: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:950
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81cb3634-ffffffff81cb3649: audit_alloc.cold (STB_LOCAL)
ffffffff811b61b0-ffffffff811b636b: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1056
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/auditsc.c:audit_alloc_kernel
```
**Symbols:**

```
ffffffff81e64472-ffffffff81e64487: audit_alloc.cold (STB_LOCAL)
ffffffff811e9890-ffffffff811e9a41: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1058
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8205c60c-ffffffff8205c621: audit_alloc.cold (STB_LOCAL)
ffffffff8122f8e0-ffffffff8122fa91: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1059
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff820daf69-ffffffff820daf7e: audit_alloc.cold (STB_LOCAL)
ffffffff812463d0-ffffffff81246581: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1057
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff821b6cbf-ffffffff821b6cd4: audit_alloc.cold (STB_LOCAL)
ffffffff81260260-ffffffff81260440: audit_alloc (STB_GLOBAL)
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
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f17d8)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff8000101f17d8-ffff8000101f197c: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0431c94)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0431c94-c0431e20: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000265a50)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c000000000265a50-c000000000265c44: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe00016516c)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe00016516c-ffffffe000165288: audit_alloc (STB_GLOBAL)
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
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81174f50)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81174f50-ffffffff811750a9: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811680f0)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811680f0-ffffffff81168249: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81172d20)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81172d20-ffffffff81172e79: audit_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_alloc(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81180580)
Location: kernel/auditsc.c:915
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81180580-ffffffff811806eb: audit_alloc (STB_GLOBAL)
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
