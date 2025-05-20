# Function: <code>fget_raw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229cd0)
Location: fs/file.c:722
Inline: True
Inline callers:
  - fs/file.c:SyS_dup
Direct callers:
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81229cd0-ffffffff81229ce2: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812536e6)
Location: fs/file.c:723
Inline: True
Inline callers:
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_get
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81252430-ffffffff81252442: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81266936)
Location: fs/file.c:723
Inline: True
Inline callers:
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_get
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812656a0-ffffffff812656b2: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81274136)
Location: fs/file.c:709
Inline: True
Inline callers:
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_get
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81272e20-ffffffff81272e32: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296a36)
Location: fs/file.c:712
Inline: True
Inline callers:
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_get
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81295750-ffffffff81295762: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bcba5)
Location: fs/file.c:708
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_get
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812bb8d0-ffffffff812bb8e2: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1e65)
Location: fs/file.c:738
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_get
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812d0ac0-ffffffff812d0ad2: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eee95)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812edaf0-ffffffff812edb07: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300955)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812ff5b0-ffffffff812ff5c7: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339b75)
Location: fs/file.c:757
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff813388a0-ffffffff813388c9: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344c95)
Location: fs/file.c:857
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81344240-ffffffff81344269: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134ae59)
Location: fs/file.c:869
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8134a5e0-ffffffff8134a609: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398bb9)
Location: fs/file.c:929
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81398380-ffffffff813983a9: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141ad20)
Location: fs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8141ad20-ffffffff8141adbe: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a6aa0)
Location: fs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff814a6aa0-ffffffff814a6b3e: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dba70)
Location: fs/file.c:932
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff814dba70-ffffffff814dbb0e: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150edab)
Location: fs/file.c:1054
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8150ebc0-ffffffff8150ec53: fget_raw (STB_GLOBAL)
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
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b28e8)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffff8000103b0e30-ffff8000103b0e64: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591be4)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
c059095c-c0590980: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae804)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
c0000000004ac460-c0000000004ac47c: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000276944)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffe000274e80-ffffffe000274eae: fget_raw (STB_GLOBAL)
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
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8f35)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812f7b90-ffffffff812f7ba7: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9b55)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812e87b0-ffffffff812e87c7: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6d45)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff812f59a0-ffffffff812f59b7: fget_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct file *fget_raw(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307fb5)
Location: fs/file.c:744
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81307370-ffffffff81307387: fget_raw (STB_GLOBAL)
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
