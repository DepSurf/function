# Function: <code>task_has_security</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int task_has_security(struct task_struct *tsk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8134a150)
Location: security/selinux/selinuxfs.c:81
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff8134a150-ffffffff8134a188: task_has_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int task_has_security(struct task_struct *tsk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8137fea0)
Location: security/selinux/selinuxfs.c:81
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8137fea0-ffffffff8137fed8: task_has_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int task_has_security(struct task_struct *tsk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81396920)
Location: security/selinux/selinuxfs.c:81
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81396920-ffffffff81396958: task_has_security (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
