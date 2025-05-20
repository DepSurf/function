# Function: <code>strnlen_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81419d10)
Location: lib/strnlen_user.c:104
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
  - mm/shmem.c:SyS_memfd_create
  - mm/util.c:strndup_user
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81419d10-ffffffff81419e0c: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81461b30)
Location: lib/strnlen_user.c:103
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
  - mm/shmem.c:SyS_memfd_create
  - mm/util.c:strndup_user
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81461b30-ffffffff81461c1f: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81480670)
Location: lib/strnlen_user.c:103
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
  - mm/shmem.c:SyS_memfd_create
  - mm/util.c:strndup_user
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81480670-ffffffff8148075f: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81489910)
Location: lib/strnlen_user.c:103
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
  - mm/shmem.c:SyS_memfd_create
  - mm/util.c:strndup_user
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81489910-ffffffff81489a04: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff814c5a60)
Location: lib/strnlen_user.c:104
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
  - mm/shmem.c:SyS_memfd_create
  - mm/util.c:strndup_user
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff814c5a60-ffffffff814c5b58: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff814f6950)
Location: lib/strnlen_user.c:104
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff814f6950-ffffffff814f6a4d: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff8150ad90)
Location: lib/strnlen_user.c:104
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff8150ad90-ffffffff8150ae8d: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff815394c0)
Location: lib/strnlen_user.c:104
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff815394c0-ffffffff815395ca: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff8155a2c0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff8155a2c0-ffffffff8155a3e6: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff815e3be0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff815e3be0-ffffffff815e3d0c: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff816080c0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff816080c0-ffffffff81608237: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff815ead70)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff815ead70-ffffffff815eae92: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81657270)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81657270-ffffffff81657393: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff8176ead0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff8176ead0-ffffffff8176ec23: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff8189e3f0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff8189e3f0-ffffffff8189e518: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff818e09c0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff818e09c0-ffffffff818e0aed: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81927500)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_user_nofault
  - mm/util.c:strndup_user
  - mm/memfd.c:__do_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81927500-ffffffff8192765d: strnlen_user (STB_GLOBAL)
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
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffff800010667060)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__arm64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffff800010667060-ffff800010667108: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (c080f7ac)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__se_sys_memfd_create
  - fs/exec.c:copy_strings
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
```
**Symbols:**

```
c080f7ac-c080f930: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (c00000000081c840)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__se_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
c00000000081c840-c00000000081ca20: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffe000492bae)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__se_sys_memfd_create
  - fs/exec.c:copy_strings
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_binary
```
**Symbols:**

```
ffffffe000492bae-ffffffe000492cc8: strnlen_user (STB_GLOBAL)
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
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff815528a0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff815528a0-ffffffff815529c6: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81542b80)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81542b80-ffffffff81542ca6: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff8154e5e0)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff8154e5e0-ffffffff8154e706: strnlen_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int strnlen_user(const char *str, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/strnlen_user.c (ffffffff81568430)
Location: lib/strnlen_user.c:92
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/maccess.c:strnlen_unsafe_user
  - mm/util.c:strndup_user
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffff81568430-ffffffff81568556: strnlen_user (STB_GLOBAL)
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
