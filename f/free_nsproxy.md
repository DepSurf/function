# Function: <code>free_nsproxy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a1120)
Location: kernel/nsproxy.c:172
Inline: False
Direct callers:
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/nsproxy.c:SyS_setns
```
**Symbols:**

```
ffffffff810a1120-ffffffff810a11a5: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a4830)
Location: kernel/nsproxy.c:172
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810a4830-ffffffff810a48d9: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810aa490)
Location: kernel/nsproxy.c:172
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810aa490-ffffffff810aa539: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a7010)
Location: kernel/nsproxy.c:173
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810a7010-ffffffff810a7092: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ad790)
Location: kernel/nsproxy.c:173
Inline: False
Direct callers:
  - kernel/nsproxy.c:SyS_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810ad790-ffffffff810ad81c: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b44f0)
Location: kernel/nsproxy.c:173
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810b44f0-ffffffff810b4586: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810bd640)
Location: kernel/nsproxy.c:173
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810bd640-ffffffff810bd6d6: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c3690)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810c3690-ffffffff810c372b: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810cc7a0)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810cc7a0-ffffffff810cc83b: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d5d20)
Location: kernel/nsproxy.c:193
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/nsproxy.c:copy_namespaces
```
**Symbols:**

```
ffffffff810d5d20-ffffffff810d5e8a: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d08f0)
Location: kernel/nsproxy.c:188
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
  - fs/io_uring.c:io_req_clean_work
  - fs/io_uring.c:io_sq_thread_drop_mm_files
```
**Symbols:**

```
ffffffff810d08f0-ffffffff810d0a91: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d24d0)
Location: kernel/nsproxy.c:188
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810d24d0-ffffffff810d2671: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810e5610)
Location: kernel/nsproxy.c:188
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810e5610-ffffffff810e57b1: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ff420)
Location: kernel/nsproxy.c:188
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810ff420-ffffffff810ff5c5: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81124140)
Location: kernel/nsproxy.c:190
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff81124140-ffffffff811242e5: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81131440)
Location: kernel/nsproxy.c:190
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff81131440-ffffffff811315e5: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8113c1d0)
Location: kernel/nsproxy.c:190
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
```
**Symbols:**

```
ffffffff8113c1d0-ffffffff8113c375: free_nsproxy (STB_GLOBAL)
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
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffff80001012b4e0)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__arm64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffff80001012b4e0-ffff80001012b5b8: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c037ba7c)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
c037ba7c-c037bb4c: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (c000000000173f50)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
c000000000173f50-c0000000001740ec: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffe0000e0318)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffe0000e0318-ffffffe0000e03c4: free_nsproxy (STB_GLOBAL)
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
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c6b20)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810c6b20-ffffffff810c6bbb: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810b5340)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810b5340-ffffffff810b53db: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810c6070)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810c6070-ffffffff810c610b: free_nsproxy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_nsproxy(struct nsproxy *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ce4c0)
Location: kernel/nsproxy.c:169
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/nsproxy.c:switch_task_namespaces
```
**Symbols:**

```
ffffffff810ce4c0-ffffffff810ce55b: free_nsproxy (STB_GLOBAL)
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
