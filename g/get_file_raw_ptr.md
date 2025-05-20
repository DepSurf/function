# Function: <code>get_file_raw_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff810e9710)
Location: kernel/kcmp.c:57
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
**Symbols:**

```
ffffffff810e9710-ffffffff810e976d: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff810f0470)
Location: kernel/kcmp.c:57
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
**Symbols:**

```
ffffffff810f0470-ffffffff810f04cb: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff810f75d0)
Location: kernel/kcmp.c:57
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
**Symbols:**

```
ffffffff810f75d0-ffffffff810f762b: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff810f93c0)
Location: kernel/kcmp.c:61
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
**Symbols:**

```
ffffffff810f93c0-ffffffff810f941b: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81103e30)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
**Symbols:**

```
ffffffff81103e30-ffffffff81103e97: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8110e8d0)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffffffff8110e8d0-ffffffff8110e93d: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81119e50)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffffffff81119e50-ffffffff81119eb9: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811248a0)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff811248a0-ffffffff81124904: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81130860)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff81130860-ffffffff811308c4: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113fb20)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffffffff8113fb20-ffffffff8113fb85: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113c3aa)
Location: kernel/kcmp.c:62
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:kcmp_epoll_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113d5de)
Location: kernel/kcmp.c:62
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8116075e)
Location: kernel/kcmp.c:62
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff8119353f)
Location: kernel/kcmp.c:62
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff811d0d7f)
Location: kernel/kcmp.c:62
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff811e5015)
Location: kernel/kcmp.c:62
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811fad6d)
Location: kernel/kcmp.c:62
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
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
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffff800010197860)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffff800010197860-ffff80001019791c: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (c03e2aec)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
**Symbols:**

```
c03e2aec-c03e2b68: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (c0000000001f7710)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
**Symbols:**

```
c0000000001f7710-c0000000001f780c: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffe000128924)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
**Symbols:**

```
ffffffe000128924-ffffffe0001289cc: get_file_raw_ptr (STB_LOCAL)
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
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81129010)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff81129010-ffffffff81129074: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8111b8a0)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8111b8a0-ffffffff8111b904: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81126d30)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff81126d30-ffffffff81126d94: get_file_raw_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *get_file_raw_ptr(struct task_struct *task, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81133380)
Location: kernel/kcmp.c:62
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff81133380-ffffffff811333ee: get_file_raw_ptr (STB_LOCAL)
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
