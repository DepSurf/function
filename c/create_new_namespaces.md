# Function: <code>create_new_namespaces</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a0eb0)
Location: kernel/nsproxy.c:63
Inline: False
Direct callers:
  - kernel/nsproxy.c:copy_namespaces
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:SyS_setns
```
**Symbols:**

```
ffffffff810a0eb0-ffffffff810a107a: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a4590)
Location: kernel/nsproxy.c:63
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810a4590-ffffffff810a4782: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810aa1f0)
Location: kernel/nsproxy.c:63
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810aa1f0-ffffffff810aa3e2: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a6db0)
Location: kernel/nsproxy.c:64
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810a6db0-ffffffff810a6f6f: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ad520)
Location: kernel/nsproxy.c:64
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810ad520-ffffffff810ad6ee: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b4290)
Location: kernel/nsproxy.c:64
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810b4290-ffffffff810b4447: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810bd3e0)
Location: kernel/nsproxy.c:64
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810bd3e0-ffffffff810bd597: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c3410)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810c3410-ffffffff810c35e4: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810cc520)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810cc520-ffffffff810cc6f4: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d5a60)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810d5a60-ffffffff810d5d14: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d0540)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810d0540-ffffffff810d081e: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d2120)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810d2120-ffffffff810d23fa: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810e5260)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810e5260-ffffffff810e553a: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ff050)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810ff050-ffffffff810ff346: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81123d40)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff81123d40-ffffffff81124036: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81131010)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff81131010-ffffffff81131305: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8113bd60)
Location: kernel/nsproxy.c:67
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff8113bd60-ffffffff8113c055: create_new_namespaces (STB_LOCAL)
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
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffff80001012b228)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__arm64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffff80001012b228-ffff80001012b410: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c037b80c)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
c037b80c-c037b9d0: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c000000000173b80)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
c000000000173b80-c000000000173e2c: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffe0000e00ee)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffe0000e00ee-ffffffe0000e028a: create_new_namespaces (STB_LOCAL)
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
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c68a0)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810c68a0-ffffffff810c6a74: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b50c0)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810b50c0-ffffffff810b5294: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c5df0)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810c5df0-ffffffff810c5fc4: create_new_namespaces (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nsproxy *create_new_namespaces(long unsigned int flags, struct task_struct *tsk, struct user_namespace *user_ns, struct fs_struct *new_fs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ce230)
Location: kernel/nsproxy.c:60
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810ce230-ffffffff810ce404: create_new_namespaces (STB_LOCAL)
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
