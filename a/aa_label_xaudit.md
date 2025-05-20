# Function: <code>aa_label_xaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138cb60)
Location: security/apparmor/label.c:1696
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8138cb60-ffffffff8138cd43: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c7900)
Location: security/apparmor/label.c:1711
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813c7900-ffffffff813c7ae6: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813deee0)
Location: security/apparmor/label.c:1726
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813deee0-ffffffff813df0c6: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ee900)
Location: security/apparmor/label.c:1710
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813ee900-ffffffff813eea70: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814165b0)
Location: security/apparmor/label.c:1710
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814165b0-ffffffff81416720: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81448980)
Location: security/apparmor/label.c:1709
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81448980-ffffffff81448b01: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814658b0)
Location: security/apparmor/label.c:1710
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814658b0-ffffffff81465a31: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81492e70)
Location: security/apparmor/label.c:1706
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81492e70-ffffffff81493005: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814acda0)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814acda0-ffffffff814acf35: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150b7f0)
Location: security/apparmor/label.c:1732
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8150b7f0-ffffffff8150b974: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815286a0)
Location: security/apparmor/label.c:1732
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff815286a0-ffffffff81528824: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152e810)
Location: security/apparmor/label.c:1732
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8152e810-ffffffff8152e994: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1732
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81cd6733-ffffffff81cd6747: aa_label_xaudit.cold (STB_LOCAL)
ffffffff8158cc00-ffffffff8158cd92: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1741
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81e89689-ffffffff81e8969d: aa_label_xaudit.cold (STB_LOCAL)
ffffffff8162de50-ffffffff8162dff7: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e2990)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff816e2990-ffffffff816e2b24: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171bf70)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lsm.c:audit_uring_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8171bf70-ffffffff8171c0e9: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8175a9c0)
Location: security/apparmor/label.c:1741
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/task.c:audit_ns_cb
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lsm.c:audit_uring_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8175a9c0-ffffffff8175ab39: aa_label_xaudit (STB_GLOBAL)
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
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a4170)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffff8000105a4170-ffff8000105a431c: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c075427c)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
c075427c-c0754430: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071fb90)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
c00000000071fb90-c00000000071fdec: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ee310)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffe0003ee310-ffffffe0003ee466: aa_label_xaudit (STB_GLOBAL)
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
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a5380)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814a5380-ffffffff814a5515: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81495da0)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81495da0-ffffffff81495f35: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a1420)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814a1420-ffffffff814a15b5: aa_label_xaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_label_xaudit(struct audit_buffer *ab, struct aa_ns *ns, struct aa_label *label, int flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b9b40)
Location: security/apparmor/label.c:1735
Inline: False
Direct callers:
  - security/apparmor/audit.c:audit_pre
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814b9b40-ffffffff814b9cd5: aa_label_xaudit (STB_GLOBAL)
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
