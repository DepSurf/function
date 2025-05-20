# Function: <code>bpf_task_fd_query_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b36b0)
Location: kernel/bpf/syscall.c:2143
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811b36b0-ffffffff811b381f: bpf_task_fd_query_copy.isra.18 (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff811c1d90)
Location: kernel/bpf/syscall.c:2462
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c1d90-ffffffff811c1eff: bpf_task_fd_query_copy.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d23c0)
Location: kernel/bpf/syscall.c:2688
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d23c0-ffffffff811d2520: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811de980)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811de980-ffffffff811deafe: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc090)
Location: kernel/bpf/syscall.c:3657
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811fc090-ffffffff811fc222: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb1b0)
Location: kernel/bpf/syscall.c:3828
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811fb1b0-ffffffff811fb374: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbfa0)
Location: kernel/bpf/syscall.c:3852
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811fbfa0-ffffffff811fc15e: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122d590)
Location: kernel/bpf/syscall.c:4035
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff8122d590-ffffffff8122d74e: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81270540)
Location: kernel/bpf/syscall.c:4296
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff81270540-ffffffff812706c8: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6020)
Location: kernel/bpf/syscall.c:4344
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff812c6020-ffffffff812c61c0: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ed0e0)
Location: kernel/bpf/syscall.c:4481
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff812ed0e0-ffffffff812ed280: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130bbd0)
Location: kernel/bpf/syscall.c:4818
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff8130bbd0-ffffffff8130bd70: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102607b8)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff8000102607b8-ffff800010261160: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr *attr, union bpf_attr *uattr, u32 prog_id, u32 fd_type, const char *buf, u64 probe_offset, u64 probe_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04935a4)
Location: kernel/bpf/syscall.c:2713
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
c04935a4-c04938d8: bpf_task_fd_query_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (c000000000305290)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c000000000305290-c0000000003057fc: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019dec4)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe00019dec4-ffffffe00019e09c: bpf_task_fd_query_copy.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6fa0)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d6fa0-ffffffff811d711e: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c9d60)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c9d60-ffffffff811c9ede: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4d70)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d4d70-ffffffff811d4eee: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e30a0)
Location: kernel/bpf/syscall.c:2713
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e30a0-ffffffff811e321e: bpf_task_fd_query_copy.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
