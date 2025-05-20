# Function: <code>lsm_slot_to_name</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *lsm_slot_to_name(int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd6af)
Location: security/security.c:525
Inline: True
Inline callers:
  - security/security.c:security_setprocattr
  - security/security.c:security_getprocattr
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - security/integrity/ima/ima_policy.c:ima_rules_lsm_init
```
**Symbols:**

```
ffffffff815b9a90-ffffffff815b9b12: lsm_slot_to_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *lsm_slot_to_name(int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665270)
Location: security/security.c:564
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - security/integrity/ima/ima_policy.c:ima_rules_lsm_init
```
**Symbols:**

```
ffffffff81665270-ffffffff816652f2: lsm_slot_to_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *lsm_slot_to_name(int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169d7f0)
Location: security/security.c:572
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - security/integrity/ima/ima_policy.c:ima_rules_lsm_init
```
**Symbols:**

```
ffffffff8169d7f0-ffffffff8169d872: lsm_slot_to_name (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
