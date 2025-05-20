# Function: <code>switch_task_namespaces</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a1260)
Location: kernel/nsproxy.c:216
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/nsproxy.c:exit_task_namespaces
  - kernel/nsproxy.c:SyS_setns
```
**Symbols:**

```
ffffffff810a1260-ffffffff810a12c3: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a4990)
Location: kernel/nsproxy.c:216
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810a4990-ffffffff810a49ec: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810aa5f0)
Location: kernel/nsproxy.c:216
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810aa5f0-ffffffff810aa64c: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a7150)
Location: kernel/nsproxy.c:217
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810a7150-ffffffff810a71b3: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ad8d0)
Location: kernel/nsproxy.c:217
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810ad8d0-ffffffff810ad933: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b4640)
Location: kernel/nsproxy.c:217
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810b4640-ffffffff810b46a3: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810bd790)
Location: kernel/nsproxy.c:217
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810bd790-ffffffff810bd7f3: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c37e0)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810c37e0-ffffffff810c3841: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810cc8f0)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810cc8f0-ffffffff810cc951: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d63c0)
Location: kernel/nsproxy.c:242
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810d63c0-ffffffff810d6421: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d0f60)
Location: kernel/nsproxy.c:237
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810d0f60-ffffffff810d0fc1: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d2b40)
Location: kernel/nsproxy.c:237
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810d2b40-ffffffff810d2ba1: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810e5c80)
Location: kernel/nsproxy.c:237
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810e5c80-ffffffff810e5ce1: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ffad0)
Location: kernel/nsproxy.c:237
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810ffad0-ffffffff810ffb4a: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81124830)
Location: kernel/nsproxy.c:239
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff81124830-ffffffff811248aa: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81131b30)
Location: kernel/nsproxy.c:239
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff81131b30-ffffffff81131baa: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8113ce86)
Location: kernel/nsproxy.c:239
Inline: True
Inline callers:
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff8113c940-ffffffff8113c9d6: switch_task_namespaces (STB_GLOBAL)
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
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffff80001012b660)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__arm64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffff80001012b660-ffff80001012b728: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c037bbf4)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
c037bbf4-c037bc78: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c0000000001741e0)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
c0000000001741e0-c0000000001742d0: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffe0000e044c)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffe0000e044c-ffffffe0000e04f2: switch_task_namespaces (STB_GLOBAL)
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
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c6c70)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810c6c70-ffffffff810c6cd1: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b5490)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810b5490-ffffffff810b54f1: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c61c0)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810c61c0-ffffffff810c6221: switch_task_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct *p, struct nsproxy *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ce610)
Location: kernel/nsproxy.c:213
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff810ce610-ffffffff810ce671: switch_task_namespaces (STB_GLOBAL)
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
