# Function: <code>calipso_sock_setattr</code>

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
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81870d70)
Location: net/ipv6/calipso.c:1143
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883970)
Location: net/netlabel/netlabel_calipso.c:554
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81870d70-ffffffff81870e24: calipso_sock_setattr (STB_LOCAL)
ffffffff81883970-ffffffff81883990: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a3ce0)
Location: net/ipv6/calipso.c:1143
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b8210)
Location: net/netlabel/netlabel_calipso.c:557
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff818a3ce0-ffffffff818a3d94: calipso_sock_setattr (STB_LOCAL)
ffffffff818b8210-ffffffff818b8230: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818ca270)
Location: net/ipv6/calipso.c:1143
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818deb00)
Location: net/netlabel/netlabel_calipso.c:557
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff818ca270-ffffffff818ca30f: calipso_sock_setattr (STB_LOCAL)
ffffffff818deb00-ffffffff818deb20: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194d9b0)
Location: net/ipv6/calipso.c:1143
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81964790)
Location: net/netlabel/netlabel_calipso.c:557
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff8194d9b0-ffffffff8194da98: calipso_sock_setattr (STB_LOCAL)
ffffffff81964790-ffffffff819647b6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a6c30)
Location: net/ipv6/calipso.c:1142
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819be030)
Location: net/netlabel/netlabel_calipso.c:557
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff819a6c30-ffffffff819a6d11: calipso_sock_setattr (STB_LOCAL)
ffffffff819be030-ffffffff819be056: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dd790)
Location: net/ipv6/calipso.c:1142
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f51d0)
Location: net/netlabel/netlabel_calipso.c:557
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff819dd790-ffffffff819dd871: calipso_sock_setattr (STB_LOCAL)
ffffffff819f51d0-ffffffff819f51f6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4c050)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a646a0)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81a4c050-ffffffff81a4c116: calipso_sock_setattr (STB_LOCAL)
ffffffff81a646a0-ffffffff81a646c6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a82c20)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9b220)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81a82c20-ffffffff81a82ce6: calipso_sock_setattr (STB_LOCAL)
ffffffff81a9b220-ffffffff81a9b246: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7da80)
Location: net/ipv6/calipso.c:1129
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96a80)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81b7da80-ffffffff81b7db7e: calipso_sock_setattr (STB_LOCAL)
ffffffff81b96a80-ffffffff81b96aa6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8cba0)
Location: net/ipv6/calipso.c:1125
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba66f0)
Location: net/netlabel/netlabel_calipso.c:545
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81b8cba0-ffffffff81b8cca9: calipso_sock_setattr (STB_LOCAL)
ffffffff81ba66f0-ffffffff81ba6716: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7b690)
Location: net/ipv6/calipso.c:1125
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95880)
Location: net/netlabel/netlabel_calipso.c:545
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81b7b690-ffffffff81b7b797: calipso_sock_setattr (STB_LOCAL)
ffffffff81b95880-ffffffff81b958a6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1125
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c620b0)
Location: net/netlabel/netlabel_calipso.c:545
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81c46650-ffffffff81c4676c: calipso_sock_setattr (STB_LOCAL)
ffffffff81d41604-ffffffff81d41624: calipso_sock_setattr.cold (STB_LOCAL)
ffffffff81c620b0-ffffffff81c620d6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1125
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e047a0)
Location: net/netlabel/netlabel_calipso.c:545
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81de5b00-ffffffff81de5c2d: calipso_sock_setattr (STB_LOCAL)
ffffffff81f0df78-ffffffff81f0df98: calipso_sock_setattr.cold (STB_LOCAL)
ffffffff81e047a0-ffffffff81e047da: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1125
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9830)
Location: net/netlabel/netlabel_calipso.c:546
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81fb8330-ffffffff81fb845d: calipso_sock_setattr (STB_LOCAL)
ffffffff820b5320-ffffffff820b5340: calipso_sock_setattr.cold (STB_LOCAL)
ffffffff81fd9830-ffffffff81fd986a: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1125
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82055500)
Location: net/netlabel/netlabel_calipso.c:546
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff82018ab0-ffffffff82018bcc: calipso_sock_setattr (STB_LOCAL)
ffffffff821361b8-ffffffff821361d1: calipso_sock_setattr.cold (STB_LOCAL)
ffffffff82055500-ffffffff8205553a: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1125
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127e20)
Location: net/netlabel/netlabel_calipso.c:549
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff820e7a80-ffffffff820e7b9c: calipso_sock_setattr (STB_LOCAL)
ffffffff82217d88-ffffffff82217da1: calipso_sock_setattr.cold (STB_LOCAL)
ffffffff82127e20-ffffffff82127e5a: calipso_sock_setattr (STB_GLOBAL)
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
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4dd68)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6afb0)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffff800010d4dd68-ffff800010d4de7c: calipso_sock_setattr (STB_LOCAL)
ffff800010d6afb0-ffff800010d6b00c: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4f710)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c0e694a8)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
c0e4f710-c0e4f7ec: calipso_sock_setattr (STB_LOCAL)
c0e694a8-c0e694e4: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e85980)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea8540)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
c000000000e85980-c000000000e85ae4: calipso_sock_setattr (STB_LOCAL)
c000000000ea8540-c000000000ea8598: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe000886c24)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d8e6)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffe000886c24-ffffffe000886d12: calipso_sock_setattr (STB_LOCAL)
ffffffe00089d8e6-ffffffe00089d92c: calipso_sock_setattr (STB_GLOBAL)
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
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a222b0)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a5b0)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81a222b0-ffffffff81a22376: calipso_sock_setattr (STB_LOCAL)
ffffffff81a3a5b0-ffffffff81a3a5d6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819df070)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f71d0)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff819df070-ffffffff819df136: calipso_sock_setattr (STB_LOCAL)
ffffffff819f71d0-ffffffff819f71f6: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8cd30)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6460)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81a8cd30-ffffffff81a8cdf6: calipso_sock_setattr (STB_LOCAL)
ffffffff81aa6460-ffffffff81aa6486: calipso_sock_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int calipso_sock_setattr(struct sock *sk, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a999c0)
Location: net/ipv6/calipso.c:1128
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2800)
Location: net/netlabel/netlabel_calipso.c:544
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_conn_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_sock_setattr
```
**Symbols:**

```
ffffffff81a999c0-ffffffff81a99ab5: calipso_sock_setattr (STB_LOCAL)
ffffffff81ab2800-ffffffff81ab2826: calipso_sock_setattr (STB_GLOBAL)
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
