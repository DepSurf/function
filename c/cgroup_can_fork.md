# Function: <code>cgroup_can_fork</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, void **ss_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811195a0)
Location: kernel/cgroup.c:5655
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811195a0-ffffffff81119682: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81121180)
Location: kernel/cgroup.c:5868
Inline: False
```
**Symbols:**

```
ffffffff81121180-ffffffff81121269: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129700)
Location: kernel/cgroup.c:5896
Inline: False
```
**Symbols:**

```
ffffffff81129700-ffffffff811297e9: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811284b0)
Location: kernel/cgroup/cgroup.c:4811
Inline: False
```
**Symbols:**

```
ffffffff811284b0-ffffffff81128586: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81134ae0)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
```
**Symbols:**

```
ffffffff81134ae0-ffffffff81134bbf: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81143200)
Location: kernel/cgroup/cgroup.c:5516
Inline: False
```
**Symbols:**

```
ffffffff81143200-ffffffff811432f3: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ed30)
Location: kernel/cgroup/cgroup.c:5609
Inline: False
```
**Symbols:**

```
ffffffff8114ed30-ffffffff8114ee23: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a8a0)
Location: kernel/cgroup/cgroup.c:5950
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8115a8a0-ffffffff8115a98e: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166550)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81166550-ffffffff8116663e: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811781e0)
Location: kernel/cgroup/cgroup.c:6052
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811781e0-ffffffff811782fa: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174f10)
Location: kernel/cgroup/cgroup.c:6044
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81174f10-ffffffff8117502a: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175a60)
Location: kernel/cgroup/cgroup.c:6019
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81175a60-ffffffff81175b6b: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d000)
Location: kernel/cgroup/cgroup.c:6235
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8119d000-ffffffff8119d152: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd330)
Location: kernel/cgroup/cgroup.c:6264
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811cd330-ffffffff811cd487: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210900)
Location: kernel/cgroup/cgroup.c:6510
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81210900-ffffffff81210a54: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81226310)
Location: kernel/cgroup/cgroup.c:6490
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81226310-ffffffff81226467: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123dfa0)
Location: kernel/cgroup/cgroup.c:6525
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8123dfa0-ffffffff8123e0f7: cgroup_can_fork (STB_GLOBAL)
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
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8278)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff8000101d8278-ffff8000101d838c: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041aeb4)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c041aeb4-c041afb4: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245260)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c000000000245260-c0000000002453dc: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe0001512b2)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe0001512b2-ffffffe00015137a: cgroup_can_fork (STB_GLOBAL)
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
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115eb70)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8115eb70-ffffffff8115ec5e: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151e10)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81151e10-ffffffff81151efe: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c940)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8115c940-ffffffff8115ca2e: cgroup_can_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_can_fork(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81169a50)
Location: kernel/cgroup/cgroup.c:5965
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81169a50-ffffffff81169b3e: cgroup_can_fork (STB_GLOBAL)
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
<b>Param removed. </b>
<code>void **ss_priv</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kernel_clone_args *kargs</code>
</li>
</ul>
</details>
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
