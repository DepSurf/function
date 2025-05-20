# Function: <code>audit_log_n_hex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81121e00)
Location: kernel/audit.c:1517
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81121e00-ffffffff81121f47: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129d40)
Location: kernel/audit.c:1528
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81129d40-ffffffff81129e9c: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133a60)
Location: kernel/audit.c:1667
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81133a60-ffffffff81133bbc: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134f40)
Location: kernel/audit.c:1846
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81134f40-ffffffff81135087: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141c90)
Location: kernel/audit.c:1854
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:common_lsm_audit
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81141c90-ffffffff81141dd7: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150640)
Location: kernel/audit.c:1907
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81150640-ffffffff81150793: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d2f0)
Location: kernel/audit.c:1904
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8115d2f0-ffffffff8115d43d: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169a30)
Location: kernel/audit.c:1904
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81169a30-ffffffff81169b7a: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811758d0)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811758d0-ffffffff81175a1a: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188030)
Location: kernel/audit.c:1986
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81188030-ffffffff8118817a: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811853c0)
Location: kernel/audit.c:2003
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811853c0-ffffffff8118550a: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811863c0)
Location: kernel/audit.c:2003
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811863c0-ffffffff8118650c: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ae7b0)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811ae7b0-ffffffff811ae8fe: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0730)
Location: kernel/audit.c:2024
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff811e0730-ffffffff811e08b3: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812264d0)
Location: kernel/audit.c:2022
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff812264d0-ffffffff81226653: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123cab0)
Location: kernel/audit.c:2022
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8123cab0-ffffffff8123cc3f: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812569c0)
Location: kernel/audit.c:2040
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff812569c0-ffffffff81256b4f: audit_log_n_hex (STB_GLOBAL)
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
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ea770)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffff8000101ea770-ffff8000101ea8e4: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a478)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
c042a478-c042a5e4: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025ba20)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
c00000000025ba20-c00000000025bc58: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f140)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffe00015f140-ffffffe00015f290: audit_log_n_hex (STB_GLOBAL)
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
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116def0)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8116def0-ffffffff8116e03a: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81161090)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81161090-ffffffff811611da: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116bcc0)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff8116bcc0-ffffffff8116be0a: audit_log_n_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_n_hex(struct audit_buffer *ab, const unsigned char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179480)
Location: kernel/audit.c:1906
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_untrustedstring
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - security/lsm_audit.c:dump_common_audit_data
  - security/apparmor/label.c:aa_label_xaudit
  - drivers/tty/tty_audit.c:tty_audit_log
```
**Symbols:**

```
ffffffff81179480-ffffffff811795ca: audit_log_n_hex (STB_GLOBAL)
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
