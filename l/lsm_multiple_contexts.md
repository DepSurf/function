# Function: <code>lsm_multiple_contexts</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187800)
Location: include/linux/security.h:249
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8118f6ff)
Location: include/linux/security.h:249
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184b70)
Location: include/linux/security.h:251
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8118c98f)
Location: include/linux/security.h:251
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185a00)
Location: include/linux/security.h:252
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8118d6c4)
Location: include/linux/security.h:252
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811adde0)
Location: include/linux/security.h:252
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff811b63b4)
Location: include/linux/security.h:252
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0d10)
Location: include/linux/security.h:229
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226b30)
Location: include/linux/security.h:249
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123d110)
Location: include/linux/security.h:249
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
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
