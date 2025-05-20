# Function: <code>audit_log_subject_context</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_log_subject_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811df710)
Location: kernel/audit.c:2228
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811df710-ffffffff811df94d: audit_log_subject_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_log_subject_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81225400)
Location: kernel/audit.c:2226
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81225400-ffffffff8122563d: audit_log_subject_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_log_subject_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123b9d0)
Location: kernel/audit.c:2226
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8123b9d0-ffffffff8123bc2b: audit_log_subject_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int audit_log_subject_context(struct audit_buffer *ab, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:2244
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff821b6c16-ffffffff821b6c2b: audit_log_subject_context.cold (STB_LOCAL)
ffffffff81255890-ffffffff81255ae9: audit_log_subject_context (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
