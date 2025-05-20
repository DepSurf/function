# Function: <code>calipso_req_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81870c70)
Location: net/ipv6/calipso.c:1207
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818839b0)
Location: net/netlabel/netlabel_calipso.c:594
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81870c70-ffffffff81870d6a: calipso_req_setattr (STB_LOCAL)
ffffffff818839b0-ffffffff818839d0: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a3be0)
Location: net/ipv6/calipso.c:1207
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b8250)
Location: net/netlabel/netlabel_calipso.c:597
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff818a3be0-ffffffff818a3cda: calipso_req_setattr (STB_LOCAL)
ffffffff818b8250-ffffffff818b8270: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818ca190)
Location: net/ipv6/calipso.c:1207
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818deb40)
Location: net/netlabel/netlabel_calipso.c:597
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff818ca190-ffffffff818ca263: calipso_req_setattr (STB_LOCAL)
ffffffff818deb40-ffffffff818deb60: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194d8d0)
Location: net/ipv6/calipso.c:1207
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819647f0)
Location: net/netlabel/netlabel_calipso.c:597
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff8194d8d0-ffffffff8194d9a9: calipso_req_setattr (STB_LOCAL)
ffffffff819647f0-ffffffff81964816: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a6b60)
Location: net/ipv6/calipso.c:1206
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819be090)
Location: net/netlabel/netlabel_calipso.c:597
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff819a6b60-ffffffff819a6c23: calipso_req_setattr (STB_LOCAL)
ffffffff819be090-ffffffff819be0b6: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dd6c0)
Location: net/ipv6/calipso.c:1206
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f5230)
Location: net/netlabel/netlabel_calipso.c:597
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff819dd6c0-ffffffff819dd781: calipso_req_setattr (STB_LOCAL)
ffffffff819f5230-ffffffff819f5256: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4bf80)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a64700)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81a4bf80-ffffffff81a4c043: calipso_req_setattr (STB_LOCAL)
ffffffff81a64700-ffffffff81a64726: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a82b50)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9b280)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81a82b50-ffffffff81a82c13: calipso_req_setattr (STB_LOCAL)
ffffffff81a9b280-ffffffff81a9b2a6: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7d9a0)
Location: net/ipv6/calipso.c:1193
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96ae0)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81b7d9a0-ffffffff81b7da7f: calipso_req_setattr (STB_LOCAL)
ffffffff81b96ae0-ffffffff81b96b06: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8cac0)
Location: net/ipv6/calipso.c:1189
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6750)
Location: net/netlabel/netlabel_calipso.c:585
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81b8cac0-ffffffff81b8cb9f: calipso_req_setattr (STB_LOCAL)
ffffffff81ba6750-ffffffff81ba6776: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7b360)
Location: net/ipv6/calipso.c:1189
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b958e0)
Location: net/netlabel/netlabel_calipso.c:585
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81b7b360-ffffffff81b7b43f: calipso_req_setattr (STB_LOCAL)
ffffffff81b958e0-ffffffff81b95906: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81c46020)
Location: net/ipv6/calipso.c:1189
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c62110)
Location: net/netlabel/netlabel_calipso.c:585
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81c46020-ffffffff81c460ff: calipso_req_setattr (STB_LOCAL)
ffffffff81c62110-ffffffff81c62136: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81de5420)
Location: net/ipv6/calipso.c:1189
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04820)
Location: net/netlabel/netlabel_calipso.c:585
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81de5420-ffffffff81de5502: calipso_req_setattr (STB_LOCAL)
ffffffff81e04820-ffffffff81e0485a: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81fb7c00)
Location: net/ipv6/calipso.c:1189
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd98d0)
Location: net/netlabel/netlabel_calipso.c:586
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81fb7c00-ffffffff81fb7ce2: calipso_req_setattr (STB_LOCAL)
ffffffff81fd98d0-ffffffff81fd990a: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820183a0)
Location: net/ipv6/calipso.c:1189
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff820555a0)
Location: net/netlabel/netlabel_calipso.c:586
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff820183a0-ffffffff82018480: calipso_req_setattr (STB_LOCAL)
ffffffff820555a0-ffffffff820555da: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820e7370)
Location: net/ipv6/calipso.c:1189
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127ec0)
Location: net/netlabel/netlabel_calipso.c:589
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff820e7370-ffffffff820e7450: calipso_req_setattr (STB_LOCAL)
ffffffff82127ec0-ffffffff82127efa: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4de80)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6b050)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffff800010d4de80-ffff800010d4df88: calipso_req_setattr (STB_LOCAL)
ffff800010d6b050-ffff800010d6b0ac: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4f620)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c0e69518)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
c0e4f620-c0e4f710: calipso_req_setattr (STB_LOCAL)
c0e69518-c0e69554: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e85800)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea85f0)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
c000000000e85800-c000000000e85978: calipso_req_setattr (STB_LOCAL)
c000000000ea85f0-c000000000ea8648: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe000886b56)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d95c)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffe000886b56-ffffffe000886c24: calipso_req_setattr (STB_LOCAL)
ffffffe00089d95c-ffffffe00089d9a2: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a221e0)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a610)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81a221e0-ffffffff81a222a3: calipso_req_setattr (STB_LOCAL)
ffffffff81a3a610-ffffffff81a3a636: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819defa0)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f7230)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff819defa0-ffffffff819df063: calipso_req_setattr (STB_LOCAL)
ffffffff819f7230-ffffffff819f7256: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8cc60)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa64c0)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81a8cc60-ffffffff81a8cd23: calipso_req_setattr (STB_LOCAL)
ffffffff81aa64c0-ffffffff81aa64e6: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int calipso_req_setattr(struct request_sock *req, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a998f0)
Location: net/ipv6/calipso.c:1192
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2860)
Location: net/netlabel/netlabel_calipso.c:584
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_req_setattr
```
**Symbols:**

```
ffffffff81a998f0-ffffffff81a999b3: calipso_req_setattr (STB_LOCAL)
ffffffff81ab2860-ffffffff81ab2886: calipso_req_setattr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
