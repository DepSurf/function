# Function: <code>close_fd</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int close_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345888)
Location: fs/file.c:619
Inline: True
Inline callers:
  - fs/file.c:replace_fd
Direct callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
```
**Symbols:**

```
ffffffff81344440-ffffffff81344482: close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int close_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134bc28)
Location: fs/file.c:619
Inline: True
Inline callers:
  - fs/file.c:replace_fd
Direct callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
```
**Symbols:**

```
ffffffff8134a7e0-ffffffff8134a822: close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int close_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399a68)
Location: fs/file.c:633
Inline: True
Inline callers:
  - fs/file.c:replace_fd
Direct callers:
  - kernel/bpf/syscall.c:bpf_sys_close
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff81398590-ffffffff813985d9: close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int close_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c485)
Location: fs/file.c:653
Inline: True
Inline callers:
  - fs/file.c:replace_fd
Direct callers:
  - kernel/bpf/syscall.c:bpf_sys_close
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff8141aa90-ffffffff8141aafb: close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int close_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a85a5)
Location: fs/file.c:653
Inline: True
Inline callers:
  - fs/file.c:replace_fd
Direct callers:
  - kernel/bpf/syscall.c:bpf_sys_close
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff814a6ce0-ffffffff814a6d4b: close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int close_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd595)
Location: fs/file.c:654
Inline: True
Inline callers:
  - fs/file.c:replace_fd
Direct callers:
  - kernel/bpf/syscall.c:bpf_sys_close
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_preload_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_release_progs
```
**Symbols:**

```
ffffffff814dbcc0-ffffffff814dbd2b: close_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int close_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff815100b5)
Location: fs/file.c:661
Inline: True
Inline callers:
  - fs/file.c:replace_fd
Direct callers:
  - kernel/bpf/syscall.c:bpf_sys_close
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_preload_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_release_progs
```
**Symbols:**

```
ffffffff8150f6a0-ffffffff8150f70b: close_fd (STB_GLOBAL)
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
