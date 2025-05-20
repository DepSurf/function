# Function: <code>aa_audit_perm_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const char **names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81378740)
Location: security/apparmor/lib.c:257
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81378740-ffffffff81378849: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const char **names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813b14a0)
Location: security/apparmor/lib.c:257
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813b14a0-ffffffff813b159f: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const char **names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813c8660)
Location: security/apparmor/lib.c:257
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813c8660-ffffffff813c875f: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813dde10)
Location: security/apparmor/lib.c:232
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813dde10-ffffffff813ddf0f: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814047b0)
Location: security/apparmor/lib.c:232
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814047b0-ffffffff814048af: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81435860)
Location: security/apparmor/lib.c:232
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81435860-ffffffff8143595f: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81452490)
Location: security/apparmor/lib.c:243
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81452490-ffffffff81452571: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8147fe50)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8147fe50-ffffffff8147ff31: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81499b50)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81499b50-ffffffff81499c31: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814f2240)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814f2240-ffffffff814f2381: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8150f440)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8150f440-ffffffff8150f581: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81515e30)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81515e30-ffffffff81515f6e: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81573e30)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81573e30-ffffffff81573f6e: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81611770)
Location: security/apparmor/lib.c:258
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81611770-ffffffff816118e1: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816c4450)
Location: security/apparmor/lib.c:350
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff816c4450-ffffffff816c45c1: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816fd020)
Location: security/apparmor/lib.c:350
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff816fd020-ffffffff816fd191: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8173a580)
Location: security/apparmor/lib.c:352
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/lib.c:aa_audit_perms
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8173a580-ffffffff8173a6f1: aa_audit_perm_mask (STB_GLOBAL)
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
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffff80001058f9b8)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffff80001058f9b8-ffff80001058fac0: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c074077c)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
c074077c-c0740888: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c000000000702db0)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
c000000000702db0-c000000000702f18: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffe0003dd5f8)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffe0003dd5f8-ffffffe0003dd6c8: aa_audit_perm_mask (STB_GLOBAL)
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
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81492130)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81492130-ffffffff81492211: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81482b50)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81482b50-ffffffff81482c31: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8148e1d0)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8148e1d0-ffffffff8148e2b1: aa_audit_perm_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_audit_perm_mask(struct audit_buffer *ab, u32 mask, const char *chrs, u32 chrsmask, const const char * *names, u32 namesmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814a60e0)
Location: security/apparmor/lib.c:239
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/lib.c:aa_audit_perms_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814a60e0-ffffffff814a61c1: aa_audit_perm_mask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char **names</code> ➡️ <code>const const char * *names</code>
</li>
</ul>
</details>
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
