# Function: <code>release_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81082430)
Location: kernel/exit.c:169
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81082430-ffffffff8108288b: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81085460)
Location: kernel/exit.c:168
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81085460-ffffffff810858d6: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108a3d0)
Location: kernel/exit.c:177
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8108a3d0-ffffffff8108a84d: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81087420)
Location: kernel/exit.c:184
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81087420-ffffffff81087843: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e1b0)
Location: kernel/exit.c:184
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8108e1b0-ffffffff8108e5d3: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810929a6)
Location: kernel/exit.c:184
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81091c70-ffffffff810920ad: release_task.part.20 (STB_LOCAL)
ffffffff81093080-ffffffff81093090: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff8109ac32)
Location: kernel/exit.c:185
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81099f60-ffffffff8109a3aa: release_task.part.20 (STB_LOCAL)
ffffffff8109b330-ffffffff8109b340: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e580)
Location: kernel/exit.c:186
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff8109e580-ffffffff8109e9d4: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a4b00)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810a4b00-ffffffff810a4f70: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ac5a0)
Location: kernel/exit.c:181
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810ac5a0-ffffffff810ac721: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7c60)
Location: kernel/exit.c:182
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810a7c60-ffffffff810a7dee: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8b40)
Location: kernel/exit.c:182
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810a8b40-ffffffff810a8cca: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ba620)
Location: kernel/exit.c:182
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810ba620-ffffffff810ba7bd: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d11b0)
Location: kernel/exit.c:186
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810d11b0-ffffffff810d1373: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810efbf0)
Location: kernel/exit.c:238
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810efbf0-ffffffff810efdb0: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fbbb0)
Location: kernel/exit.c:239
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810fbbb0-ffffffff810fbd70: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff811050b0)
Location: kernel/exit.c:242
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff811050b0-ffffffff81105275: release_task (STB_GLOBAL)
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
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fa950)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffff8000100fa950-ffff8000100fae70: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035875c)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
c035875c-c0358cc4: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000141c70)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
c000000000141c70-c000000000142200: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c4784)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffe0000c4784-ffffffe0000c4bdc: release_task (STB_GLOBAL)
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
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e420)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff8109e420-ffffffff8109e890: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108ce30)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff8108ce30-ffffffff8108d2b9: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e3d0)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff8109e3d0-ffffffff8109e840: release_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a62e0)
Location: kernel/exit.c:191
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810a62e0-ffffffff810a675c: release_task (STB_GLOBAL)
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
