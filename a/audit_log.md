# Function: <code>audit_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81121ab0)
Location: kernel/audit.c:2006
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_init
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_mls_copy
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81121ab0-ffffffff81121b38: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811299f0)
Location: kernel/audit.c:2027
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811299f0-ffffffff81129a78: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133710)
Location: kernel/audit.c:2146
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81133710-ffffffff81133798: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134c00)
Location: kernel/audit.c:2325
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_init
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81134c00-ffffffff81134c8d: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141950)
Location: kernel/audit.c:2333
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81141950-ffffffff811419dd: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811502d0)
Location: kernel/audit.c:2375
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811502d0-ffffffff81150358: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115cf90)
Location: kernel/audit.c:2372
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8115cf90-ffffffff8115d018: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811696b0)
Location: kernel/audit.c:2337
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811696b0-ffffffff8116973a: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175550)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81175550-ffffffff811755da: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187c00)
Location: kernel/audit.c:2491
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validtrans_handle_fail
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81187c00-ffffffff81187cbd: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184f70)
Location: kernel/audit.c:2508
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validtrans_handle_fail
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81184f70-ffffffff8118502d: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185e00)
Location: kernel/audit.c:2508
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81185e00-ffffffff81185ebd: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ae1f0)
Location: kernel/audit.c:2547
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811ae1f0-ffffffff811ae2ad: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e00d0)
Location: kernel/audit.c:2599
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811e00d0-ffffffff811e0186: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81225e40)
Location: kernel/audit.c:2597
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81225e40-ffffffff81225ef6: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123c420)
Location: kernel/audit.c:2597
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8123c420-ffffffff8123c4d6: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81256300)
Location: kernel/audit.c:2619
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81256300-ffffffff812563b6: audit_log (STB_GLOBAL)
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
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ea328)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffff8000101ea328-ffff8000101ea3ec: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a104)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
c042a104-c042a180: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025b4f0)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
c00000000025b4f0-c00000000025b560: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015ee10)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffe00015ee10-ffffffe00015ee7a: audit_log (STB_GLOBAL)
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
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116db70)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8116db70-ffffffff8116dbfa: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81160d10)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81160d10-ffffffff81160d9a: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b940)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8116b940-ffffffff8116b9ca: audit_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log(struct audit_context *ctx, gfp_t gfp_mask, int type, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179110)
Location: kernel/audit.c:2339
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81179110-ffffffff8117919a: audit_log (STB_GLOBAL)
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
