# Function: <code>lsmblob_is_set</code>

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
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118926d)
Location: include/linux/security.h:207
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8118f800)
Location: include/linux/security.h:207
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
```
**Symbols:**

```
ffffffff811864f0-ffffffff81186540: lsmblob_is_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811865f0)
Location: include/linux/security.h:209
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8118ca90)
Location: include/linux/security.h:209
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
```
**Symbols:**

```
ffffffff811835d0-ffffffff81183626: lsmblob_is_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811875a1)
Location: include/linux/security.h:210
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8118d7cc)
Location: include/linux/security.h:210
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
```
**Symbols:**

```
ffffffff81184700-ffffffff8118475e: lsmblob_is_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811afa01)
Location: include/linux/security.h:210
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff811b64bc)
Location: include/linux/security.h:210
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_lsm
```
**Symbols:**

```
ffffffff811aca10-ffffffff811aca6e: lsmblob_is_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811df756)
Location: include/linux/security.h:194
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff811e8bb9)
Location: include/linux/security.h:194
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff811de570-ffffffff811de5d6: lsmblob_is_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81225446)
Location: include/linux/security.h:214
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8122ec49)
Location: include/linux/security.h:214
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff812240f0-ffffffff81224156: lsmblob_is_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ba16)
Location: include/linux/security.h:214
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff81244b39)
Location: include/linux/security.h:214
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff8123a6d0-ffffffff8123a736: lsmblob_is_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool lsmblob_is_set(struct lsmblob *blob);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812558cf)
Location: include/linux/security.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffffffff8125ea72)
Location: include/linux/security.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_pid_context
```
**Symbols:**

```
ffffffff812543a0-ffffffff81254417: lsmblob_is_set (STB_LOCAL)
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
