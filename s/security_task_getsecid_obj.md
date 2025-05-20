# Function: <code>security_task_getsecid_obj</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_task_getsecid_obj(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbe30)
Location: security/security.c:2028
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
**Symbols:**

```
ffffffff814cbe30-ffffffff814cbe9e: security_task_getsecid_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_task_getsecid_obj(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524db0)
Location: security/security.c:2036
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
**Symbols:**

```
ffffffff81524db0-ffffffff81524e1e: security_task_getsecid_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_task_getsecid_obj(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8d50)
Location: security/security.c:2042
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
**Symbols:**

```
ffffffff815b8d50-ffffffff815b8dc8: security_task_getsecid_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_task_getsecid_obj(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664420)
Location: security/security.c:2094
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
**Symbols:**

```
ffffffff81664420-ffffffff81664498: security_task_getsecid_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_task_getsecid_obj(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c8c0)
Location: security/security.c:3410
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
```
**Symbols:**

```
ffffffff8169c8c0-ffffffff8169c964: security_task_getsecid_obj (STB_GLOBAL)
```
</details>
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
</ul>
