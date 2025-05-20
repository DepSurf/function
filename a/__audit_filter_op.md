# Function: <code>__audit_filter_op</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __audit_filter_op(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list, struct audit_names *name, long unsigned int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:829
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8122e530-ffffffff8122e68a: __audit_filter_op (STB_LOCAL)
ffffffff8205c5d7-ffffffff8205c5f1: __audit_filter_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __audit_filter_op(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list, struct audit_names *name, long unsigned int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:830
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff81244530-ffffffff81244676: __audit_filter_op (STB_LOCAL)
ffffffff820daf34-ffffffff820daf4e: __audit_filter_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __audit_filter_op(struct task_struct *tsk, struct audit_context *ctx, struct list_head *list, struct audit_names *name, long unsigned int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:827
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:__audit_free
```
**Symbols:**

```
ffffffff8125e420-ffffffff8125e566: __audit_filter_op (STB_LOCAL)
ffffffff821b6c8a-ffffffff821b6ca4: __audit_filter_op.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
