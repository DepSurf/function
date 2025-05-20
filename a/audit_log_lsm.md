# Function: <code>audit_log_lsm</code>

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
void audit_log_lsm(struct lsmblob *blob, bool exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f6c0)
Location: kernel/auditsc.c:1428
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8118f6c0-ffffffff8118f83b: audit_log_lsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_lsm(struct lsmblob *blob, bool exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118c950)
Location: kernel/auditsc.c:1446
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8118c950-ffffffff8118cacf: audit_log_lsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_lsm(struct lsmblob *blob, bool exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d680)
Location: kernel/auditsc.c:1445
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8118d680-ffffffff8118d811: audit_log_lsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_lsm(struct lsmblob *blob, bool exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b6370)
Location: kernel/auditsc.c:1454
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_exit
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811b6370-ffffffff811b6501: audit_log_lsm (STB_GLOBAL)
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
