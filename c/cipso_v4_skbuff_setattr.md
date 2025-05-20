# Function: <code>cipso_v4_skbuff_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff817aeea0)
Location: net/ipv4/cipso_ipv4.c:2225
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff817aeea0-ffffffff817af114: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff8181bd90)
Location: net/ipv4/cipso_ipv4.c:2156
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff8181bd90-ffffffff8181c019: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff8184d650)
Location: net/ipv4/cipso_ipv4.c:2160
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff8184d650-ffffffff8184d8d9: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81871090)
Location: net/ipv4/cipso_ipv4.c:2168
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81871090-ffffffff8187133e: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff818f1a80)
Location: net/ipv4/cipso_ipv4.c:2158
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff818f1a80-ffffffff818f1d2e: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2158
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81948706-ffffffff81948712: cipso_v4_skbuff_setattr.cold.37 (STB_LOCAL)
ffffffff819483b0-ffffffff8194862d: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2175
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff8197a3e3-ffffffff8197a3ef: cipso_v4_skbuff_setattr.cold.38 (STB_LOCAL)
ffffffff8197a090-ffffffff8197a307: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2161
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff819e3f24-ffffffff819e3f30: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff819e3bc0-ffffffff819e3e4b: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a1af14-ffffffff81a1af20: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81a1abb0-ffffffff81a1ae3b: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2175
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81b0bf87-ffffffff81b0bf93: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81b0bc10-ffffffff81b0be9d: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2168
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81c32a6c-ffffffff81c32a78: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81b19fa0-ffffffff81b1a22e: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2169
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81c24d66-ffffffff81c24d72: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81b07c40-ffffffff81b07ed1: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2168
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81d3ecdd-ffffffff81d3ece9: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81bcab40-ffffffff81bcadd1: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2169
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81f0b626-ffffffff81f0b632: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81d60490-ffffffff81d6073b: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81f2ac30)
Location: net/ipv4/cipso_ipv4.c:2169
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81f2ac30-ffffffff81f2aee7: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81f8a8f0)
Location: net/ipv4/cipso_ipv4.c:2169
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81f8a8f0-ffffffff81f8abb9: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff82052000)
Location: net/ipv4/cipso_ipv4.c:2163
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff82052000-ffffffff820522c9: cipso_v4_skbuff_setattr (STB_GLOBAL)
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
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffff800010cd6c30)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffff800010cd6c30-ffff800010cd6e88: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (c0de0984)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
c0de0984-c0de0ba8: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (c000000000df6880)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
c000000000df6880-c000000000df6b84: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffe0008275a0)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffe0008275a0-ffffffe000827784: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff819ba5a4-ffffffff819ba5b0: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff819ba240-ffffffff819ba4cb: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81977394-ffffffff819773a0: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81977030-ffffffff819772bb: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a25024-ffffffff81a25030: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81a24cc0-ffffffff81a24f4b: cipso_v4_skbuff_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cipso_v4_skbuff_setattr(struct sk_buff *skb, const struct cipso_v4_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/cipso_ipv4.c (0)
Location: net/ipv4/cipso_ipv4.c:2166
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
**Symbols:**

```
ffffffff81a30494-ffffffff81a304a0: cipso_v4_skbuff_setattr.cold (STB_LOCAL)
ffffffff81a30130-ffffffff81a303bb: cipso_v4_skbuff_setattr (STB_GLOBAL)
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
