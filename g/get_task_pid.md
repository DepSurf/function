# Function: <code>get_task_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109dba0)
Location: kernel/pid.c:464
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:SyS_waitpid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff8109dba0-ffffffff8109dbcf: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1200)
Location: kernel/pid.c:464
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:SyS_waitpid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810a1200-ffffffff810a122f: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a62c0)
Location: kernel/pid.c:464
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:SyS_waitpid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810a62c0-ffffffff810a62ef: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a32a0)
Location: kernel/pid.c:465
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810a32a0-ffffffff810a32cf: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9af0)
Location: kernel/pid.c:334
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810a9af0-ffffffff810a9b21: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0710)
Location: kernel/pid.c:359
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810b0710-ffffffff810b0740: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9840)
Location: kernel/pid.c:368
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810b9840-ffffffff810b9875: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf8a0)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810bf8a0-ffffffff810bf8d7: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5c70)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810c5c70-ffffffff810c5caa: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd560)
Location: kernel/pid.c:437
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810cd560-ffffffff810cd5e2: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8090)
Location: kernel/pid.c:438
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810c8090-ffffffff810c8103: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9b30)
Location: kernel/pid.c:438
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810c9b30-ffffffff810c9ba3: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dcaa0)
Location: kernel/pid.c:438
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810dcaa0-ffffffff810dcb2a: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f62c0)
Location: kernel/pid.c:438
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810f62c0-ffffffff810f6363: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81118920)
Location: kernel/pid.c:438
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81118920-ffffffff811189c3: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81125b60)
Location: kernel/pid.c:441
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81125b60-ffffffff81125c03: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81130160)
Location: kernel/pid.c:441
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid_prepare
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81130160-ffffffff81130203: get_task_pid (STB_GLOBAL)
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
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124158)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffff800010124158-ffff8000101241b0: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377470)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
c0377470-c03774b8: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016db00)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
c00000000016db00-c00000000016db54: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc156)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffe0000dc156-ffffffe0000dc19e: get_task_pid (STB_GLOBAL)
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
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfff0)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810bfff0-ffffffff810c002a: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae800)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810ae800-ffffffff810ae83a: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf540)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810bf540-ffffffff810bf57a: get_task_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pid *get_task_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7910)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - fs/proc/base.c:proc_pid_make_inode
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff810c7910-ffffffff810c7964: get_task_pid (STB_GLOBAL)
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
