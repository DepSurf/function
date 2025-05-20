# Function: <code>find_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109daa0)
Location: kernel/pid.c:366
Inline: False
Direct callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/pid.c:find_ge_pid
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff8109daa0-ffffffff8109db14: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1100)
Location: kernel/pid.c:366
Inline: False
Direct callers:
  - kernel/pid.c:find_ge_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810a1100-ffffffff810a1172: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a61c0)
Location: kernel/pid.c:366
Inline: False
Direct callers:
  - kernel/pid.c:find_ge_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810a61c0-ffffffff810a6232: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a31a0)
Location: kernel/pid.c:367
Inline: False
Direct callers:
  - kernel/pid.c:find_ge_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810a31a0-ffffffff810a3220: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9e20)
Location: kernel/pid.c:244
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810a9d90-ffffffff810a9daa: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0a3e)
Location: kernel/pid.c:256
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810b09a0-ffffffff810b09ba: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9b0e)
Location: kernel/pid.c:258
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810b9a80-ffffffff810b9a9a: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf87a)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810bf7f0-ffffffff810bf80a: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5c4a)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810c5bc0-ffffffff810c5bda: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd621)
Location: kernel/pid.c:308
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810cd460-ffffffff810cd47a: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c81ed)
Location: kernel/pid.c:309
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810c7ef0-ffffffff810c7f09: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9d0d)
Location: kernel/pid.c:309
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810c9990-ffffffff810c99a9: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dcbfd)
Location: kernel/pid.c:309
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810dc8f0-ffffffff810dc909: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f7570)
Location: kernel/pid.c:309
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810f60b0-ffffffff810f60d0: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119cf0)
Location: kernel/pid.c:309
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff81118640-ffffffff81118660: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81125e01)
Location: kernel/pid.c:312
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff81125880-ffffffff811258a0: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81130401)
Location: kernel/pid.c:312
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff8112fe80-ffffffff8112fea0: find_pid_ns (STB_GLOBAL)
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
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124260)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffff8000101241b0-ffff8000101241e4: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377c4c)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
  - kernel/pid.c:find_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
c03774b8-c03774e0: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016df34)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
c00000000016de50-c00000000016de90: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc4a8)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffe0000dc40a-ffffffe0000dc43e: find_pid_ns (STB_GLOBAL)
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
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bffca)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810bff40-ffffffff810bff5a: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae7da)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810ae750-ffffffff810ae76a: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf51a)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810bf490-ffffffff810bf4aa: find_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_pid_ns(int nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7824)
Location: kernel/pid.c:261
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff810c7720-ffffffff810c773a: find_pid_ns (STB_GLOBAL)
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
