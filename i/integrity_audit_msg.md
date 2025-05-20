# Function: <code>integrity_audit_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff813964a0)
Location: security/integrity/integrity_audit.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff813964a0-ffffffff81396679: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff813d2220)
Location: security/integrity/integrity_audit.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff813d2220-ffffffff813d23f9: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff813e9940)
Location: security/integrity/integrity_audit.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff813e9940-ffffffff813e9b19: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff813f5d40)
Location: security/integrity/integrity_audit.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff813f5d40-ffffffff813f5f1b: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8141de40)
Location: security/integrity/integrity_audit.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff8141de40-ffffffff8141e020: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff814500f0)
Location: security/integrity/integrity_audit.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff814500f0-ffffffff814502d0: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8146d0d0)
Location: security/integrity/integrity_audit.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff8146d0d0-ffffffff8146d268: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8149a7c0)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff8149a7c0-ffffffff8149a966: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff814b49c0)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff814b49c0-ffffffff814b4b66: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff81513f10)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff81513f10-ffffffff815140b8: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff81531220)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff81531220-ffffffff81531238: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff81539650)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff81539650-ffffffff81539668: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff81597e90)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
  - security/integrity/evm/evm_main.c:evm_protect_xattr
  - security/integrity/evm/evm_main.c:evm_protect_xattr
```
**Symbols:**

```
ffffffff81597e90-ffffffff81597ea8: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8163c690)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
  - security/integrity/evm/evm_main.c:evm_protect_xattr
  - security/integrity/evm/evm_main.c:evm_protect_xattr
```
**Symbols:**

```
ffffffff8163c690-ffffffff8163c6bc: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff816f3ef0)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
  - security/integrity/evm/evm_main.c:evm_inode_set_acl
```
**Symbols:**

```
ffffffff816f3ef0-ffffffff816f3f1c: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8172e020)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
  - security/integrity/evm/evm_main.c:evm_inode_set_acl
```
**Symbols:**

```
ffffffff8172e020-ffffffff8172e04c: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8176e980)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
  - security/integrity/evm/evm_main.c:evm_inode_set_acl
```
**Symbols:**

```
ffffffff8176e980-ffffffff8176e9ac: integrity_audit_msg (STB_GLOBAL)
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
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffff8000105acb18)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffff8000105acb18-ffff8000105acccc: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (c075c3a4)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
c075c3a4-c075c58c: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (c00000000072af60)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
c00000000072af60-c00000000072b19c: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffe0003f5196)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffe0003f5196-ffffffe0003f5310: integrity_audit_msg (STB_GLOBAL)
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
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff814acfa0)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff814acfa0-ffffffff814ad146: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8149d9c0)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff8149d9c0-ffffffff8149db66: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff814a9040)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff814a9040-ffffffff814a91e6: integrity_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff814c1a50)
Location: security/integrity/integrity_audit.c:28
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_template
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff814c1a50-ffffffff814c1bf6: integrity_audit_msg (STB_GLOBAL)
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
