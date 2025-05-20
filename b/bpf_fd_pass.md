# Function: <code>bpf_fd_pass</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cdd40)
Location: security/selinux/hooks.c:6125
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff813cdd40-ffffffff813cddc4: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb3f0)
Location: security/selinux/hooks.c:6791
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff813fb3f0-ffffffff813fb482: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814178a0)
Location: security/selinux/hooks.c:6442
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814178a0-ffffffff81417938: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814454e0)
Location: security/selinux/hooks.c:6645
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814454e0-ffffffff81445578: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145f070)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff8145f070-ffffffff8145f108: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b2070)
Location: security/selinux/hooks.c:6751
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814b2070-ffffffff814b2107: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cf3f0)
Location: security/selinux/hooks.c:6767
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814cf3f0-ffffffff814cf487: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d5b30)
Location: security/selinux/hooks.c:6932
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814d5b30-ffffffff814d5bbd: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152e670)
Location: security/selinux/hooks.c:6919
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff8152e670-ffffffff8152e6fd: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c2f90)
Location: security/selinux/hooks.c:6817
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff815c2f90-ffffffff815c3057: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8166f860)
Location: security/selinux/hooks.c:6834
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff8166f860-ffffffff8166f927: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a7dd0)
Location: security/selinux/hooks.c:6756
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff816a7dd0-ffffffff816a7e8d: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_fd_pass(const struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e4840)
Location: security/selinux/hooks.c:6920
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff816e4840-ffffffff816e48fd: bpf_fd_pass (STB_LOCAL)
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
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054c1d0)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffff80001054c1d0-ffff80001054c2ac: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0702498)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
c0702498-c070255c: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a4af0)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
c0000000006a4af0-c0000000006a4bf4: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a68c2)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffe0003a68c2-ffffffe0003a696e: bpf_fd_pass (STB_LOCAL)
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
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81457650)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff81457650-ffffffff814576e8: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81448080)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff81448080-ffffffff81448118: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814536f0)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814536f0-ffffffff81453788: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bpf_fd_pass(struct file *file, u32 sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146b1f0)
Location: security/selinux/hooks.c:6703
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff8146b1f0-ffffffff8146b288: bpf_fd_pass (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct file *file</code> ➡️ <code>const struct file *file</code>
</li>
</ul>
</details>
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
