# Function: <code>bpf_link_new_fd</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200de0)
Location: kernel/bpf/syscall.c:2459
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_fd_by_id
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81201330-ffffffff81201356: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201459)
Location: kernel/bpf/syscall.c:2475
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81200c20-ffffffff81200c46: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201f20)
Location: kernel/bpf/syscall.c:2483
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81201670-ffffffff81201696: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812340fa)
Location: kernel/bpf/syscall.c:2593
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff812335e0-ffffffff81233606: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81277786)
Location: kernel/bpf/syscall.c:2842
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81277ae0-ffffffff81277b12: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cdac0)
Location: kernel/bpf/syscall.c:2876
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff812cdeb0-ffffffff812cdee2: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f50b2)
Location: kernel/bpf/syscall.c:2995
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff812f5440-ffffffff812f5472: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_link_new_fd(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81313eae)
Location: kernel/bpf/syscall.c:3059
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81314240-ffffffff81314272: bpf_link_new_fd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
