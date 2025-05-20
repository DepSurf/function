# Function: <code>update_rlimit_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f4180)
Location: kernel/time/posix-cpu-timers.c:22
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff810f4180-ffffffff810f4205: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fb300)
Location: kernel/time/posix-cpu-timers.c:22
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff810fb300-ffffffff810fb385: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81108c80)
Location: kernel/time/posix-cpu-timers.c:21
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81108c80-ffffffff81108d05: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8110ae40)
Location: kernel/time/posix-cpu-timers.c:27
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8110ae40-ffffffff8110aec5: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81115ff0)
Location: kernel/time/posix-cpu-timers.c:28
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81115ff0-ffffffff81116075: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81122820)
Location: kernel/time/posix-cpu-timers.c:29
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81122820-ffffffff811228a5: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112df00)
Location: kernel/time/posix-cpu-timers.c:29
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8112df00-ffffffff8112df85: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81138920)
Location: kernel/time/posix-cpu-timers.c:29
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81138920-ffffffff81138997: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811445f0)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff811445f0-ffffffff81144667: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81153a70)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff81153a70-ffffffff81153ad6: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114fee0)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff8114fee0-ffffffff8114ff46: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81151310)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff81151310-ffffffff81151376: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811756e0)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff811756e0-ffffffff81175746: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811aa610)
Location: kernel/time/posix-cpu-timers.c:42
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff811aa610-ffffffff811aa6bb: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea6b0)
Location: kernel/time/posix-cpu-timers.c:42
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff811ea6b0-ffffffff811ea75b: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fede0)
Location: kernel/time/posix-cpu-timers.c:42
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff811fede0-ffffffff811fee8b: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:42
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
**Symbols:**

```
ffffffff821b5cf1-ffffffff821b5d06: update_rlimit_cpu.cold (STB_LOCAL)
ffffffff81215130-ffffffff81215203: update_rlimit_cpu (STB_GLOBAL)
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
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101aeb50)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffff8000101aeb50-ffff8000101aec30: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f9cac)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
c03f9cac-c03f9d54: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c0000000002131a0)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
c0000000002131a0-c000000000213278: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013852a)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffe00013852a-ffffffe0001385c6: update_rlimit_cpu (STB_GLOBAL)
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
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113cda0)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8113cda0-ffffffff8113ce17: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112f8f0)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8112f8f0-ffffffff8112f961: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113aac0)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8113aac0-ffffffff8113ab37: update_rlimit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_rlimit_cpu(struct task_struct *task, long unsigned int rlim_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81147580)
Location: kernel/time/posix-cpu-timers.c:38
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81147580-ffffffff811475ee: update_rlimit_cpu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
