# Function: <code>audit_log_task_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811214b0)
Location: kernel/audit.c:1828
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_config_change
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff811214b0-ffffffff8112155d: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129400)
Location: kernel/audit.c:1839
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81129400-ffffffff811294af: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133180)
Location: kernel/audit.c:1978
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81133180-ffffffff8113322f: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134740)
Location: kernel/audit.c:2145
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81134740-ffffffff811347ef: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141500)
Location: kernel/audit.c:2153
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81141500-ffffffff811415af: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114fe90)
Location: kernel/audit.c:2206
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff8114fe90-ffffffff8114ff3f: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115cb60)
Location: kernel/audit.c:2204
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff8115cb60-ffffffff8115cc0f: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169250)
Location: kernel/audit.c:2057
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81169250-ffffffff81169301: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811750f0)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff811750f0-ffffffff811751a1: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811872f0)
Location: kernel/audit.c:2139
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811872f0-ffffffff8118743f: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184660)
Location: kernel/audit.c:2156
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - security/integrity/integrity_audit.c:integrity_audit_message
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81184660-ffffffff8118478c: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185420)
Location: kernel/audit.c:2156
Inline: True
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - security/integrity/integrity_audit.c:integrity_audit_message
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81185420-ffffffff81185562: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ad810)
Location: kernel/audit.c:2195
Inline: True
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - security/integrity/integrity_audit.c:integrity_audit_message
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811ad810-ffffffff811ad952: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e2bae)
Location: kernel/audit.c:2281
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_uring
  - security/integrity/integrity_audit.c:integrity_audit_message
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff811df950-ffffffff811df9be: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81228a8e)
Location: kernel/audit.c:2279
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_uring
  - security/integrity/integrity_audit.c:integrity_audit_message
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81225650-ffffffff812256be: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123f08e)
Location: kernel/audit.c:2279
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_uring
  - security/integrity/integrity_audit.c:integrity_audit_message
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff8123bc40-ffffffff8123bcae: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81258ef6)
Location: kernel/audit.c:2299
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:audit_log_uring
  - security/integrity/integrity_audit.c:integrity_audit_message
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81255b00-ffffffff81255b79: audit_log_task_context (STB_GLOBAL)
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
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e9e50)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffff8000101e9e50-ffff8000101e9f14: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0429c44)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
c0429c44-c0429d18: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025aeb0)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
c00000000025aeb0-c00000000025afa0: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015ea24)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffe00015ea24-ffffffe00015ead0: audit_log_task_context (STB_GLOBAL)
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
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d710)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff8116d710-ffffffff8116d7c1: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811608b0)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff811608b0-ffffffff81160961: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b4e0)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff8116b4e0-ffffffff8116b591: audit_log_task_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_log_task_context(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81178cd0)
Location: kernel/audit.c:2059
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
**Symbols:**

```
ffffffff81178cd0-ffffffff81178d81: audit_log_task_context (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct lsmblob *blob</code>
</li>
</ul>
</details>
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
