# Function: <code>audit_log_lost</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81120cb0)
Location: kernel/audit.c:253
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_skb
  - kernel/audit.c:audit_printk_skb
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_string
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81120cb0-ffffffff81120d62: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81128c00)
Location: kernel/audit.c:251
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_send_skb
  - kernel/audit.c:audit_printk_skb
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81128c00-ffffffff81128cb2: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81132860)
Location: kernel/audit.c:257
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81132860-ffffffff81132912: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133fd0)
Location: kernel/audit.c:322
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81133fd0-ffffffff81134082: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140d90)
Location: kernel/audit.c:322
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81140d90-ffffffff81140e42: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:365
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81152470-ffffffff81152493: audit_log_lost.cold.24 (STB_LOCAL)
ffffffff8114f750-ffffffff8114f7e6: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8115c457)
Location: kernel/audit.c:361
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff8115f118-ffffffff8115f13b: audit_log_lost.cold.24 (STB_LOCAL)
ffffffff8115c430-ffffffff8115c4c6: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81168b28)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff8116b70a-ffffffff8116b72d: audit_log_lost.cold (STB_LOCAL)
ffffffff81168b00-ffffffff81168b96: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811749c8)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff811775ea-ffffffff8117760d: audit_log_lost.cold (STB_LOCAL)
ffffffff811749a0-ffffffff81174a36: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:349
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_buf_get
```
**Symbols:**

```
ffffffff8118a25e-ffffffff8118a281: audit_log_lost.cold (STB_LOCAL)
ffffffff81186a10-ffffffff81186aaa: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:354
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_buf_get
```
**Symbols:**

```
ffffffff81be48e4-ffffffff81be4907: audit_log_lost.cold (STB_LOCAL)
ffffffff81183d30-ffffffff81183dca: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:354
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81bd6745-ffffffff81bd6768: audit_log_lost.cold (STB_LOCAL)
ffffffff81184c60-ffffffff81184cfa: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:354
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81cb347f-ffffffff81cb34a2: audit_log_lost.cold (STB_LOCAL)
ffffffff811acf80-ffffffff811ad01a: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:356
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81e642b0-ffffffff81e642d3: audit_log_lost.cold (STB_LOCAL)
ffffffff811debd0-ffffffff811dec85: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81224810)
Location: kernel/audit.c:354
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81224810-ffffffff812248e7: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ade0)
Location: kernel/audit.c:354
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff8123ade0-ffffffff8123aeb7: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81254ca0)
Location: kernel/audit.c:354
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81254ca0-ffffffff81254d77: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e94c0)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffff8000101e94c0-ffff8000101e9620: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0429428)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
c0429428-c0429500: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025a2d0)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
c00000000025a2d0-c00000000025a414: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015e29e)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffe00015e29e-ffffffe00015e384: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116cfe8)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff8116fc0a-ffffffff8116fc2d: audit_log_lost.cold (STB_LOCAL)
ffffffff8116cfc0-ffffffff8116d056: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81160188)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81162daa-ffffffff81162dcd: audit_log_lost.cold (STB_LOCAL)
ffffffff81160160-ffffffff811601f6: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116adb8)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff8116d9da-ffffffff8116d9fd: audit_log_lost.cold (STB_LOCAL)
ffffffff8116ad90-ffffffff8116ae26: audit_log_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_lost(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811785c8)
Location: kernel/audit.c:348
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff8117b1ca-ffffffff8117b1ed: audit_log_lost.cold (STB_LOCAL)
ffffffff811785a0-ffffffff81178636: audit_log_lost (STB_GLOBAL)
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
