# Function: <code>seq_escape</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812315a0)
Location: fs/seq_file.c:384
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - fs/namespace.c:generic_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_mountinfo
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff812315a0-ffffffff81231641: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259f00)
Location: fs/seq_file.c:387
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_path
  - fs/namespace.c:generic_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff81259f00-ffffffff81259fa1: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126d470)
Location: fs/seq_file.c:394
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_path
  - fs/namespace.c:generic_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff8126d470-ffffffff8126d511: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127ac60)
Location: fs/seq_file.c:380
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff8127ac60-ffffffff8127acfd: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129d6d0)
Location: fs/seq_file.c:384
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff8129d6d0-ffffffff8129d769: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c3840)
Location: fs/seq_file.c:387
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff812c3840-ffffffff812c38d9: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d8a90)
Location: fs/seq_file.c:375
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff812d8a90-ffffffff812d8b29: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6f20)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff812f6f20-ffffffff812f6fb6: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81308f60)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff81308f60-ffffffff81308ff6: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341a40)
Location: fs/seq_file.c:352
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff81341a40-ffffffff81341ad9: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e100)
Location: fs/seq_file.c:368
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff8134e100-ffffffff8134e199: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813544d0)
Location: fs/seq_file.c:371
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff813544d0-ffffffff8135456c: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2c10)
Location: fs/seq_file.c:396
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff813a2c10-ffffffff813a2c4c: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c2ba1)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cfca2)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff8144d32d)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/ext4/super.c (ffffffff81524113)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff815c54bb)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
```
```
In lib/dynamic_debug.c (ffffffff817605df)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81206ec1)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812136a2)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff814db8fd)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/ext4/super.c (ffffffff815c1789)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff816720d9)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121c4a1)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228fb2)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff8150fe9d)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/ext4/super.c (ffffffff815f8ef1)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff816aa624)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81232efc)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240e02)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff8154434d)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/ext4/super.c (ffffffff81631a7b)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff816e75c4)
Location: include/linux/seq_file.h:150
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
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
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bca38)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffff8000103bca38-ffff8000103bcb04: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c059a580)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
c059a580-c059a630: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004ba880)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
c0000000004ba880-c0000000004ba99c: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027e3b4)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffe00027e3b4-ffffffe00027e43c: seq_escape (STB_GLOBAL)
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
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81301540)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff81301540-ffffffff813015d6: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f2160)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff812f2160-ffffffff812f21f6: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812ff330)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff812ff330-ffffffff812ff3c6: seq_escape (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void seq_escape(struct seq_file *m, const char *s, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81310670)
Location: fs/seq_file.c:376
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff81310670-ffffffff81310706: seq_escape (STB_GLOBAL)
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
