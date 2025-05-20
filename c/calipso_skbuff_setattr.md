# Function: <code>calipso_skbuff_setattr</code>

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
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8186fa70)
Location: net/ipv6/calipso.c:1314
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883a30)
Location: net/netlabel/netlabel_calipso.c:673
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff8186fa70-ffffffff8186fd26: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81883a30-ffffffff81883a50: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a29e0)
Location: net/ipv6/calipso.c:1314
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b82d0)
Location: net/netlabel/netlabel_calipso.c:676
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff818a29e0-ffffffff818a2c96: calipso_skbuff_setattr (STB_LOCAL)
ffffffff818b82d0-ffffffff818b82f0: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818c8f90)
Location: net/ipv6/calipso.c:1314
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818debc0)
Location: net/netlabel/netlabel_calipso.c:676
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff818c8f90-ffffffff818c927a: calipso_skbuff_setattr (STB_LOCAL)
ffffffff818debc0-ffffffff818debe0: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194c630)
Location: net/ipv6/calipso.c:1314
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819648b0)
Location: net/netlabel/netlabel_calipso.c:676
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff8194c630-ffffffff8194c91a: calipso_skbuff_setattr (STB_LOCAL)
ffffffff819648b0-ffffffff819648d6: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a5690)
Location: net/ipv6/calipso.c:1311
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819be150)
Location: net/netlabel/netlabel_calipso.c:676
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff819a5690-ffffffff819a59ac: calipso_skbuff_setattr (STB_LOCAL)
ffffffff819be150-ffffffff819be176: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dc120)
Location: net/ipv6/calipso.c:1311
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f52f0)
Location: net/netlabel/netlabel_calipso.c:676
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff819dc120-ffffffff819dc439: calipso_skbuff_setattr (STB_LOCAL)
ffffffff819f52f0-ffffffff819f5316: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4ada0)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a647c0)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a4ada0-ffffffff81a4b070: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81a647c0-ffffffff81a647e6: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a81970)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9b340)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a81970-ffffffff81a81c40: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81a9b340-ffffffff81a9b366: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7cd70)
Location: net/ipv6/calipso.c:1298
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96ba0)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81b7cd70-ffffffff81b7d040: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81b96ba0-ffffffff81b96bc6: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8be20)
Location: net/ipv6/calipso.c:1294
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6810)
Location: net/netlabel/netlabel_calipso.c:664
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81b8be20-ffffffff81b8c0f0: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81ba6810-ffffffff81ba6836: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7aca0)
Location: net/ipv6/calipso.c:1294
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b959a0)
Location: net/netlabel/netlabel_calipso.c:664
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81b7aca0-ffffffff81b7af6a: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81b959a0-ffffffff81b959c6: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81c45960)
Location: net/ipv6/calipso.c:1294
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c621d0)
Location: net/netlabel/netlabel_calipso.c:664
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81c45960-ffffffff81c45c2a: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81c621d0-ffffffff81c621f6: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81de4a80)
Location: net/ipv6/calipso.c:1294
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04910)
Location: net/netlabel/netlabel_calipso.c:664
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81de4a80-ffffffff81de4dc2: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81e04910-ffffffff81e0494a: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81fb7200)
Location: net/ipv6/calipso.c:1294
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9a00)
Location: net/netlabel/netlabel_calipso.c:665
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81fb7200-ffffffff81fb7542: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81fd9a00-ffffffff81fd9a3a: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff82017940)
Location: net/ipv6/calipso.c:1294
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff820556d0)
Location: net/netlabel/netlabel_calipso.c:665
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff82017940-ffffffff82017c9f: calipso_skbuff_setattr (STB_LOCAL)
ffffffff820556d0-ffffffff8205570a: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820e6910)
Location: net/ipv6/calipso.c:1294
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127ff0)
Location: net/netlabel/netlabel_calipso.c:668
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff820e6910-ffffffff820e6c6f: calipso_skbuff_setattr (STB_LOCAL)
ffffffff82127ff0-ffffffff8212802a: calipso_skbuff_setattr (STB_GLOBAL)
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
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4d118)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6b190)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffff800010d4d118-ffff800010d4d3a8: calipso_skbuff_setattr (STB_LOCAL)
ffff800010d6b190-ffff800010d6b1ec: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4e764)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c0e69600)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
c0e4e764-c0e4e9c8: calipso_skbuff_setattr (STB_LOCAL)
c0e69600-c0e6963c: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e84130)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea8760)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
c000000000e84130-c000000000e84488: calipso_skbuff_setattr (STB_LOCAL)
c000000000ea8760-c000000000ea87b8: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe000885fa0)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089da42)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffe000885fa0-ffffffe0008861f8: calipso_skbuff_setattr (STB_LOCAL)
ffffffe00089da42-ffffffe00089da88: calipso_skbuff_setattr (STB_GLOBAL)
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
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a21000)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a6d0)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a21000-ffffffff81a212d0: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81a3a6d0-ffffffff81a3a6f6: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dddc0)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f72f0)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff819dddc0-ffffffff819de090: calipso_skbuff_setattr (STB_LOCAL)
ffffffff819f72f0-ffffffff819f7316: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8ba80)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6580)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a8ba80-ffffffff81a8bd50: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81aa6580-ffffffff81aa65a6: calipso_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int calipso_skbuff_setattr(struct sk_buff *skb, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a98910)
Location: net/ipv6/calipso.c:1297
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2920)
Location: net/netlabel/netlabel_calipso.c:663
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a98910-ffffffff81a98be0: calipso_skbuff_setattr (STB_LOCAL)
ffffffff81ab2920-ffffffff81ab2946: calipso_skbuff_setattr (STB_GLOBAL)
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
