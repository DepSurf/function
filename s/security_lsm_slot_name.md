# Function: <code>security_lsm_slot_name</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *security_lsm_slot_name(int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9080)
Location: security/security.c:497
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff814a9080-ffffffff814a90b0: security_lsm_slot_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *security_lsm_slot_name(int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6680)
Location: security/security.c:499
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff814c6680-ffffffff814c66b0: security_lsm_slot_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *security_lsm_slot_name(int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc780)
Location: security/security.c:502
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff814cc780-ffffffff814cc7b0: security_lsm_slot_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *security_lsm_slot_name(int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815258c0)
Location: security/security.c:502
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff815258c0-ffffffff8152592a: security_lsm_slot_name (STB_GLOBAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
