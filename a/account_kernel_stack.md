# Function: <code>account_kernel_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void account_kernel_stack(struct thread_info *ti, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107d980)
Location: kernel/fork.c:220
Inline: False
Direct callers:
  - kernel/fork.c:free_task
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8107d980-ffffffff8107d9ef: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void account_kernel_stack(long unsigned int *stack, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fac0)
Location: kernel/fork.c:221
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8107fac0-ffffffff8107fb70: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810841f0)
Location: kernel/fork.c:285
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff810841f0-ffffffff81084338: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081250)
Location: kernel/fork.c:309
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81081250-ffffffff81081383: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087b40)
Location: kernel/fork.c:315
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81087b40-ffffffff81087c73: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108aeb0)
Location: kernel/fork.c:341
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff8108aeb0-ffffffff8108b08e: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093020)
Location: kernel/fork.c:360
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81093020-ffffffff81093187: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097160)
Location: kernel/fork.c:366
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81097160-ffffffff81097289: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109cc40)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff8109cc40-ffffffff8109cd42: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3880)
Location: kernel/fork.c:379
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff810a3880-ffffffff810a3978: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fbf0)
Location: kernel/fork.c:382
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff8109fbf0-ffffffff8109fc6c: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1430)
Location: kernel/fork.c:383
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff810a1430-ffffffff810a14d6: account_kernel_stack (STB_LOCAL)
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
In kernel/fork.c (ffffffff810b2850)
Location: kernel/fork.c:383
Inline: True
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff810b2850-ffffffff810b28e9: account_kernel_stack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c91b8)
Location: kernel/fork.c:495
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
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
In kernel/fork.c (ffffffff810e66a8)
Location: kernel/fork.c:493
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2011)
Location: kernel/fork.c:557
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f9ae0)
Location: kernel/fork.c:537
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
```
**Symbols:**

```
ffffffff810f9ae0-ffffffff810f9b5b: account_kernel_stack (STB_LOCAL)
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
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1028)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffff8000100f1028-ffff8000100f1130: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c035017c)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:free_task
```
**Symbols:**

```
c035017c-c03501e8: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000136c60)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
c000000000136c60-c000000000136d00: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000be6d8)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:release_task_stack
```
**Symbols:**

```
ffffffe0000be6d8-ffffffe0000be750: account_kernel_stack (STB_LOCAL)
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
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096560)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81096560-ffffffff81096662: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084fe0)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81084fe0-ffffffff810850e2: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096510)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81096510-ffffffff81096612: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct *tsk, int account);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e0f0)
Location: kernel/fork.c:375
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff8109e0f0-ffffffff8109e1f2: account_kernel_stack (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *stack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct thread_info *ti</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *stack</code>
</li>
</ul>
</details>
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
