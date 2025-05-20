# Function: <code>calipso_sock_getattr</code>

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
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818709d0)
Location: net/ipv6/calipso.c:1090
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883950)
Location: net/netlabel/netlabel_calipso.c:530
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff818709d0-ffffffff81870ade: calipso_sock_getattr (STB_LOCAL)
ffffffff81883950-ffffffff81883970: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a3940)
Location: net/ipv6/calipso.c:1090
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b81f0)
Location: net/netlabel/netlabel_calipso.c:533
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff818a3940-ffffffff818a3a4e: calipso_sock_getattr (STB_LOCAL)
ffffffff818b81f0-ffffffff818b8210: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818c9f20)
Location: net/ipv6/calipso.c:1090
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818deae0)
Location: net/netlabel/netlabel_calipso.c:533
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff818c9f20-ffffffff818ca005: calipso_sock_getattr (STB_LOCAL)
ffffffff818deae0-ffffffff818deb00: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194d600)
Location: net/ipv6/calipso.c:1090
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81964760)
Location: net/netlabel/netlabel_calipso.c:533
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff8194d600-ffffffff8194d750: calipso_sock_getattr (STB_LOCAL)
ffffffff81964760-ffffffff81964786: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a6170)
Location: net/ipv6/calipso.c:1089
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819be000)
Location: net/netlabel/netlabel_calipso.c:533
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff819a6170-ffffffff819a62c7: calipso_sock_getattr (STB_LOCAL)
ffffffff819be000-ffffffff819be026: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dcf60)
Location: net/ipv6/calipso.c:1089
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f51a0)
Location: net/netlabel/netlabel_calipso.c:533
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff819dcf60-ffffffff819dd0b7: calipso_sock_getattr (STB_LOCAL)
ffffffff819f51a0-ffffffff819f51c6: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4bbb0)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a64670)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81a4bbb0-ffffffff81a4bcc3: calipso_sock_getattr (STB_LOCAL)
ffffffff81a64670-ffffffff81a64696: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a82780)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9b1f0)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81a82780-ffffffff81a82893: calipso_sock_getattr (STB_LOCAL)
ffffffff81a9b1f0-ffffffff81a9b216: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7d6a0)
Location: net/ipv6/calipso.c:1076
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96a50)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81b7d6a0-ffffffff81b7d802: calipso_sock_getattr (STB_LOCAL)
ffffffff81b96a50-ffffffff81b96a76: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8c7c0)
Location: net/ipv6/calipso.c:1072
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba66c0)
Location: net/netlabel/netlabel_calipso.c:521
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81b8c7c0-ffffffff81b8c92c: calipso_sock_getattr (STB_LOCAL)
ffffffff81ba66c0-ffffffff81ba66e6: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7b900)
Location: net/ipv6/calipso.c:1072
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95850)
Location: net/netlabel/netlabel_calipso.c:521
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81b7b900-ffffffff81b7ba69: calipso_sock_getattr (STB_LOCAL)
ffffffff81b95850-ffffffff81b95876: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1072
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c62080)
Location: net/netlabel/netlabel_calipso.c:521
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81c46260-ffffffff81c463d5: calipso_sock_getattr (STB_LOCAL)
ffffffff81d415a4-ffffffff81d415c4: calipso_sock_getattr.cold (STB_LOCAL)
ffffffff81c62080-ffffffff81c620a6: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1072
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04760)
Location: net/netlabel/netlabel_calipso.c:521
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81de5690-ffffffff81de5840: calipso_sock_getattr (STB_LOCAL)
ffffffff81f0df18-ffffffff81f0df38: calipso_sock_getattr.cold (STB_LOCAL)
ffffffff81e04760-ffffffff81e04796: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1072
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd97e0)
Location: net/netlabel/netlabel_calipso.c:522
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81fb7e90-ffffffff81fb8040: calipso_sock_getattr (STB_LOCAL)
ffffffff820b52c0-ffffffff820b52e0: calipso_sock_getattr.cold (STB_LOCAL)
ffffffff81fd97e0-ffffffff81fd9816: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1072
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff820554b0)
Location: net/netlabel/netlabel_calipso.c:522
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff82018620-ffffffff820187c1: calipso_sock_getattr (STB_LOCAL)
ffffffff8213616d-ffffffff82136186: calipso_sock_getattr.cold (STB_LOCAL)
ffffffff820554b0-ffffffff820554e6: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (0)
Location: net/ipv6/calipso.c:1072
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127dd0)
Location: net/netlabel/netlabel_calipso.c:525
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff820e75f0-ffffffff820e7791: calipso_sock_getattr (STB_LOCAL)
ffffffff82217d3d-ffffffff82217d56: calipso_sock_getattr.cold (STB_LOCAL)
ffffffff82127dd0-ffffffff82127e06: calipso_sock_getattr (STB_GLOBAL)
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
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4eb20)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6af60)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffff800010d4eb20-ffff800010d4ec64: calipso_sock_getattr (STB_LOCAL)
ffff800010d6af60-ffff800010d6afac: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4f3b4)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c0e6946c)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
c0e4f3b4-c0e4f4b0: calipso_sock_getattr (STB_LOCAL)
c0e6946c-c0e694a8: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e853d0)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea84e0)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
c000000000e853d0-c000000000e855e8: calipso_sock_getattr (STB_LOCAL)
c000000000ea84e0-c000000000ea8538: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe0008871ce)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d8a8)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffe0008871ce-ffffffe0008872e2: calipso_sock_getattr (STB_LOCAL)
ffffffe00089d8a8-ffffffe00089d8e6: calipso_sock_getattr (STB_GLOBAL)
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
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a21e10)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a580)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81a21e10-ffffffff81a21f23: calipso_sock_getattr (STB_LOCAL)
ffffffff81a3a580-ffffffff81a3a5a6: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819debd0)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f71a0)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff819debd0-ffffffff819dece3: calipso_sock_getattr (STB_LOCAL)
ffffffff819f71a0-ffffffff819f71c6: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8c890)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6430)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81a8c890-ffffffff81a8c9a3: calipso_sock_getattr (STB_LOCAL)
ffffffff81aa6430-ffffffff81aa6456: calipso_sock_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int calipso_sock_getattr(struct sock *sk, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a99630)
Location: net/ipv6/calipso.c:1075
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab27d0)
Location: net/netlabel/netlabel_calipso.c:520
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_sock_getattr
```
**Symbols:**

```
ffffffff81a99630-ffffffff81a9975a: calipso_sock_getattr (STB_LOCAL)
ffffffff81ab27d0-ffffffff81ab27f6: calipso_sock_getattr (STB_GLOBAL)
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
