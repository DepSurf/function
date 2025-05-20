# Function: <code>security_task_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e1a0)
Location: security/security.c:862
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8133e1a0-ffffffff8133e1d6: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373800)
Location: security/security.c:884
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81373800-ffffffff81373836: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a130)
Location: security/security.c:905
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8138a130-ffffffff8138a166: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f5a0)
Location: security/security.c:1526
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8139f5a0-ffffffff8139f5ef: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5060)
Location: security/security.c:1482
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff813c5060-ffffffff813c50b5: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f52f0)
Location: security/security.c:1001
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff813f52f0-ffffffff813f5324: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410720)
Location: security/security.c:1544
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff81410720-ffffffff8141076d: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dec0)
Location: security/security.c:1563
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff8143dec0-ffffffff8143df0f: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457970)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff81457970-ffffffff814579bd: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa880)
Location: security/security.c:1790
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff814aa8d0-ffffffff814aa91d: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7e80)
Location: security/security.c:1792
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff814c7ed0-ffffffff814c7f1d: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce4c0)
Location: security/security.c:1842
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff814ce510-ffffffff814ce55d: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527180)
Location: security/security.c:1850
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff815271d0-ffffffff8152721d: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bbdcf)
Location: security/security.c:1855
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff815bbe80-ffffffff815bbed5: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667c8f)
Location: security/security.c:1902
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81667d50-ffffffff81667da5: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a02af)
Location: security/security.c:3019
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff816a0370-ffffffff816a03c5: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dccce)
Location: security/security.c:3085
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff816dcd60-ffffffff816dcdb5: security_task_free (STB_GLOBAL)
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
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543610)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffff800010543610-ffff800010543664: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f958c)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
c06f958c-c06f95e4: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697700)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
c000000000697700-c00000000069778c: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039fb12)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffe00039fb12-ffffffe00039fb5e: security_task_free (STB_GLOBAL)
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
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ff50)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff8144ff50-ffffffff8144ff9d: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814409a0)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff814409a0-ffffffff814409ed: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144bff0)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff8144bff0-ffffffff8144c03d: security_task_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_task_free(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814633c0)
Location: security/security.c:1602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff814633c0-ffffffff8146340d: security_task_free (STB_GLOBAL)
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
