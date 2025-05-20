# Function: <code>netlbl_audit_start_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff8180b280)
Location: net/netlabel/netlabel_user.c:92
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8180b280-ffffffff8180b364: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff8187cdb0)
Location: net/netlabel/netlabel_user.c:97
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8187cdb0-ffffffff8187ce94: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff818b1660)
Location: net/netlabel/netlabel_user.c:97
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff818b1660-ffffffff818b1744: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff818d8010)
Location: net/netlabel/netlabel_user.c:97
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff818d8010-ffffffff818d80f4: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff8195dc00)
Location: net/netlabel/netlabel_user.c:97
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8195dc00-ffffffff8195dce4: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff819b7410)
Location: net/netlabel/netlabel_user.c:97
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff819b7410-ffffffff819b74ec: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff819ee6d0)
Location: net/netlabel/netlabel_user.c:97
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff819ee6d0-ffffffff819ee7ac: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81a5d910)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81a5d910-ffffffff81a5d9e8: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81a94540)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81a94540-ffffffff81a94618: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81b8fb20)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81b8fb20-ffffffff81b8fbbd: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81b9f760)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81b9f760-ffffffff81b9f7fd: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81b8e830)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81b8e830-ffffffff81b8e8cd: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81c5adc0)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81c5adc0-ffffffff81c5ae5d: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81dfc8d0)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81dfc8d0-ffffffff81dfc972: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81fd12d0)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81fd12d0-ffffffff81fd1372: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff8204cee0)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8204cee0-ffffffff8204cf6c: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff8211f380)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8211f380-ffffffff8211f40c: netlbl_audit_start_common (STB_GLOBAL)
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
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffff800010d62cf0)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffff800010d62cf0-ffff800010d62de0: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (c0e61c34)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c0e61c34-c0e61d38: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (c000000000e9e070)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c000000000e9e070-c000000000e9e1d4: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffe00089718c)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffe00089718c-ffffffe000897254: netlbl_audit_start_common (STB_GLOBAL)
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
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81a338d0)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81a338d0-ffffffff81a339a8: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff819f04f0)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff819f04f0-ffffffff819f05c8: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81a9f780)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81a9f780-ffffffff81a9f858: netlbl_audit_start_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct audit_buffer *netlbl_audit_start_common(int type, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_user.c (ffffffff81aab980)
Location: net/netlabel/netlabel_user.c:83
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_audit_start
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81aab980-ffffffff81aaba58: netlbl_audit_start_common (STB_GLOBAL)
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
