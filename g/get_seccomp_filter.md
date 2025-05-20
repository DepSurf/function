# Function: <code>get_seccomp_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8113b610)
Location: kernel/seccomp.c:461
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8113b610-ffffffff8113b62a: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811446b0)
Location: kernel/seccomp.c:461
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff81143dd0-ffffffff81143dea: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114e550)
Location: kernel/seccomp.c:460
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff8114dc90-ffffffff8114dcaa: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81150beb)
Location: kernel/seccomp.c:476
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff811502c0-ffffffff811502da: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115cb0f)
Location: kernel/seccomp.c:484
Inline: True
```
**Symbols:**

```
ffffffff8115d150-ffffffff8115d16e: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116bec1)
Location: kernel/seccomp.c:493
Inline: True
```
**Symbols:**

```
ffffffff8116bff0-ffffffff8116c00d: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811798d0)
Location: kernel/seccomp.c:553
Inline: True
```
**Symbols:**

```
ffffffff81179a10-ffffffff81179a2d: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81186068)
Location: kernel/seccomp.c:558
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811867f0-ffffffff8118680d: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81192374)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81192770-ffffffff8119278d: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a6f09)
Location: kernel/seccomp.c:569
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_seccomp
```
**Symbols:**

```
ffffffff811a7580-ffffffff811a75c4: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4466)
Location: kernel/seccomp.c:911
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_seccomp
```
**Symbols:**

```
ffffffff811a4d10-ffffffff811a4d93: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4f66)
Location: kernel/seccomp.c:916
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811a5970-ffffffff811a59f3: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811ce6b6)
Location: kernel/seccomp.c:919
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811cf0c0-ffffffff811cf143: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812027ca)
Location: kernel/seccomp.c:925
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81203240-ffffffff812032db: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8124a61a)
Location: kernel/seccomp.c:925
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8124b0f0-ffffffff8124b18b: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8126191a)
Location: kernel/seccomp.c:925
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81262410-ffffffff812624ab: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127bb1a)
Location: kernel/seccomp.c:934
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8127c650-ffffffff8127c6eb: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010209bc8)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff80001020a0e0-ffff80001020a110: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0448778)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0448f90-c0448fb8: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c000000000286f08)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c000000000287540-c000000000287568: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016b938)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe00016bf06-ffffffe00016bf32: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8118a994)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8118ad90-ffffffff8118adad: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117dabe)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8117deb0-ffffffff8117decd: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81188764)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81188b60-ffffffff81188b7d: get_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void get_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811960d2)
Location: kernel/seccomp.c:559
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811964d0-ffffffff811964ed: get_seccomp_filter (STB_GLOBAL)
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
