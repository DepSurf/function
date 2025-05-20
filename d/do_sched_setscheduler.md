# Function: <code>do_sched_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa0e0)
Location: kernel/sched/core.c:4087
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setscheduler
  - kernel/sched/core.c:SyS_sched_setparam
```
**Symbols:**

```
ffffffff810aa0e0-ffffffff810aa189: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810acd60)
Location: kernel/sched/core.c:4337
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setparam
  - kernel/sched/core.c:SyS_sched_setscheduler
```
**Symbols:**

```
ffffffff810acd60-ffffffff810ace09: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2df0)
Location: kernel/sched/core.c:4374
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setparam
  - kernel/sched/core.c:SyS_sched_setscheduler
```
**Symbols:**

```
ffffffff810b2df0-ffffffff810b2e99: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aed10)
Location: kernel/sched/core.c:4274
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setparam
  - kernel/sched/core.c:SyS_sched_setscheduler
```
**Symbols:**

```
ffffffff810aed10-ffffffff810aedb4: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5f50)
Location: kernel/sched/core.c:4318
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setparam
  - kernel/sched/core.c:SyS_sched_setscheduler
```
**Symbols:**

```
ffffffff810b5f50-ffffffff810b5ff4: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bdbb0)
Location: kernel/sched/core.c:4453
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810bdbb0-ffffffff810bdc54: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6d60)
Location: kernel/sched/core.c:4438
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810c6d60-ffffffff810c6e04: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd2b0)
Location: kernel/sched/core.c:4875
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810cd2b0-ffffffff810cd357: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6ca0)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810d6ca0-ffffffff810d6d85: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1580)
Location: kernel/sched/core.c:5323
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810e1580-ffffffff810e16b3: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de900)
Location: kernel/sched/core.c:6142
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810de900-ffffffff810dea3c: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e04f0)
Location: kernel/sched/core.c:6443
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810e04f0-ffffffff810e062c: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5760)
Location: kernel/sched/core.c:7607
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810f5760-ffffffff810f589c: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81112220)
Location: kernel/sched/core.c:7715
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff81112220-ffffffff8111238e: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81139250)
Location: kernel/sched/core.c:7857
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff81139250-ffffffff811393be: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811484c0)
Location: kernel/sched/core.c:7966
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff811484c0-ffffffff8114862e: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81153bf0)
Location: kernel/sched/core.c:8027
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff81153bf0-ffffffff81153d5e: do_sched_setscheduler (STB_LOCAL)
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
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101374c8)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__arm64_sys_sched_setparam
  - kernel/sched/core.c:__arm64_sys_sched_setscheduler
```
**Symbols:**

```
ffff8000101374c8-ffff8000101375bc: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03863f8)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_setparam
  - kernel/sched/core.c:__se_sys_sched_setscheduler
```
**Symbols:**

```
c03863f8-c0386544: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000182aa0)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_setparam
  - kernel/sched/core.c:__se_sys_sched_setscheduler
```
**Symbols:**

```
c000000000182aa0-c000000000182c40: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7c28)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_setparam
  - kernel/sched/core.c:__se_sys_sched_setscheduler
```
**Symbols:**

```
ffffffe0000e7c28-ffffffe0000e7cdc: do_sched_setscheduler (STB_LOCAL)
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
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1270)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810d1270-ffffffff810d1355: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf5e0)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810bf5e0-ffffffff810bf6c5: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf330)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810cf330-ffffffff810cf415: do_sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_sched_setscheduler(pid_t pid, int policy, struct sched_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8950)
Location: kernel/sched/core.c:5090
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setparam
  - kernel/sched/core.c:__x64_sys_sched_setparam
  - kernel/sched/core.c:__ia32_sys_sched_setscheduler
  - kernel/sched/core.c:__x64_sys_sched_setscheduler
```
**Symbols:**

```
ffffffff810d8950-ffffffff810d8a3f: do_sched_setscheduler (STB_LOCAL)
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
