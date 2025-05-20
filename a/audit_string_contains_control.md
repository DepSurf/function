# Function: <code>audit_string_contains_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81122060)
Location: kernel/audit.c:1583
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
```
**Symbols:**

```
ffffffff81122060-ffffffff811220b1: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129ff5)
Location: kernel/audit.c:1594
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
```
**Symbols:**

```
ffffffff81129fb0-ffffffff81129fe4: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133d15)
Location: kernel/audit.c:1733
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
```
**Symbols:**

```
ffffffff81133cd0-ffffffff81133d04: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811351f5)
Location: kernel/audit.c:1912
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
```
**Symbols:**

```
ffffffff811351b0-ffffffff811351e6: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141f45)
Location: kernel/audit.c:1920
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/net.c:audit_unix_addr
```
**Symbols:**

```
ffffffff81141f00-ffffffff81141f36: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150905)
Location: kernel/audit.c:1973
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811508c0-ffffffff811508f6: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d5a5)
Location: kernel/audit.c:1970
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff8115d560-ffffffff8115d597: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169cd5)
Location: kernel/audit.c:1970
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81169c90-ffffffff81169cc7: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175b75)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81175b30-ffffffff81175b67: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188305)
Location: kernel/audit.c:2052
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811882c0-ffffffff811882f7: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185665)
Location: kernel/audit.c:2069
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81185620-ffffffff81185657: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186665)
Location: kernel/audit.c:2069
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81186620-ffffffff81186657: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811aea55)
Location: kernel/audit.c:2108
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811aea10-ffffffff811aea47: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0a55)
Location: kernel/audit.c:2090
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811e0a00-ffffffff811e0a4b: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226825)
Location: kernel/audit.c:2088
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff812267c0-ffffffff8122680b: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ce05)
Location: kernel/audit.c:2088
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff8123cda0-ffffffff8123cdeb: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81256d15)
Location: kernel/audit.c:2106
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff81256cb0-ffffffff81256cfb: audit_string_contains_control (STB_GLOBAL)
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
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eaabc)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffff8000101eaa28-ffff8000101eaa94: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a774)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
c042a6fc-c042a760: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025bee0)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
c00000000025be60-c00000000025bec8: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f424)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffe00015f3a4-ffffffe00015f406: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e195)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff8116e150-ffffffff8116e187: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81161335)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811612f0-ffffffff81161327: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116bf65)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff8116bf20-ffffffff8116bf57: audit_string_contains_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool audit_string_contains_control(const char *string, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179725)
Location: kernel/audit.c:1972
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_untrustedstring
Direct callers:
  - kernel/auditsc.c:audit_log_execve_info
  - security/apparmor/label.c:aa_label_xaudit
```
**Symbols:**

```
ffffffff811796e0-ffffffff81179717: audit_string_contains_control (STB_GLOBAL)
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
