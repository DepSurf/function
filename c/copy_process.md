# Function: <code>copy_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *copy_process(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int *child_tidptr, struct pid *pid, int trace, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107e5f0)
Location: kernel/fork.c:1248
Inline: False
Direct callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:_do_fork
```
**Symbols:**

```
ffffffff8107e5f0-ffffffff810800b7: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81081fc6)
Location: kernel/fork.c:1304
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff810802f0-ffffffff81081e5d: copy_process.part.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81086a26)
Location: kernel/fork.c:1460
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81084c50-ffffffff810868bd: copy_process.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81083776)
Location: kernel/fork.c:1528
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81081b30-ffffffff81083601: copy_process.part.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff8108a056)
Location: kernel/fork.c:1539
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81088400-ffffffff81089eea: copy_process.part.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff8108d87f)
Location: kernel/fork.c:1610
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff8108c150-ffffffff8108d728: copy_process.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81095b0f)
Location: kernel/fork.c:1680
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81093a10-ffffffff810959c7: copy_process.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81098130)
Location: kernel/fork.c:1775
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81098130-ffffffff81099cbb: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e700)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff8109e700-ffffffff810a0266: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5df0)
Location: kernel/fork.c:1847
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff810a5df0-ffffffff810a7144: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a17d0)
Location: kernel/fork.c:1858
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff810a17d0-ffffffff810a2e1e: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2550)
Location: kernel/fork.c:1857
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:create_io_thread
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff810a2550-ffffffff810a3a1e: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3c50)
Location: kernel/fork.c:1936
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:create_io_thread
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff810b3c50-ffffffff810b523c: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9f10)
Location: kernel/fork.c:1981
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:create_io_thread
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff810c9f10-ffffffff810cb521: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e7580)
Location: kernel/fork.c:2015
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:create_io_thread
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff810e7580-ffffffff810e8aee: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f3140)
Location: kernel/fork.c:2248
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:create_io_thread
  - kernel/fork.c:fork_idle
  - kernel/vhost_task.c:vhost_task_create
```
**Symbols:**

```
ffffffff810f3140-ffffffff810f474f: copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc4f0)
Location: kernel/fork.c:2245
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:create_io_thread
  - kernel/fork.c:fork_idle
  - kernel/vhost_task.c:vhost_task_create
```
**Symbols:**

```
ffffffff810fc4f0-ffffffff810fdae3: copy_process (STB_GLOBAL)
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
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3598)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffff8000100f3598-ffff8000100f4aac: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0351a04)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
c0351a04-c035323c: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001390d0)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
c0000000001390d0-c00000000013aab4: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bfbc8)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffe0000bfbc8-ffffffe0000c0f22: copy_process (STB_LOCAL)
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
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81098020)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81098020-ffffffff81099b86: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086a80)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81086a80-ffffffff810885c8: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097fd0)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff81097fd0-ffffffff81099b36: copy_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *copy_process(struct pid *pid, int trace, int node, struct kernel_clone_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fbd0)
Location: kernel/fork.c:1766
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:fork_idle
```
**Symbols:**

```
ffffffff8109fbd0-ffffffff810a1782: copy_process (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
