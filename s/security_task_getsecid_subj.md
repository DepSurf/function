# Function: <code>security_task_getsecid_subj</code>

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
void security_task_getsecid_subj(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbdc0)
Location: security/security.c:2015
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_log_lsm
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff814cbdc0-ffffffff814cbe2e: security_task_getsecid_subj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_task_getsecid_subj(struct task_struct *p, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524d40)
Location: security/security.c:2023
Inline: False
Direct callers:
  - kernel/audit.c:audit_signal_info
  - kernel/auditfilter.c:audit_filter
  - kernel/auditsc.c:audit_log_lsm
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
**Symbols:**

```
ffffffff81524d40-ffffffff81524dae: security_task_getsecid_subj (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
