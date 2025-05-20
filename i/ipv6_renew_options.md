# Function: <code>ipv6_renew_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt, int newoptlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff817f3d00)
Location: net/ipv6/exthdrs.c:762
Inline: False
```
**Symbols:**

```
ffffffff817f3d00-ffffffff817f4033: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt, int newoptlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81862c20)
Location: net/ipv6/exthdrs.c:810
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
```
**Symbols:**

```
ffffffff81862c20-ffffffff81862f55: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt, int newoptlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81895230)
Location: net/ipv6/exthdrs.c:1026
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
```
**Symbols:**

```
ffffffff81895230-ffffffff81895565: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt, int newoptlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818bb7a0)
Location: net/ipv6/exthdrs.c:1028
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
```
**Symbols:**

```
ffffffff818bb7a0-ffffffff818bbad0: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt, int newoptlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff8193e860)
Location: net/ipv6/exthdrs.c:1078
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
```
**Symbols:**

```
ffffffff8193e860-ffffffff8193eb90: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819977a0)
Location: net/ipv6/exthdrs.c:1057
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff819977a0-ffffffff81997ab0: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819ce070)
Location: net/ipv6/exthdrs.c:1057
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff819ce070-ffffffff819ce381: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a3cc80)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81a3cc80-ffffffff81a3cfaf: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a73900)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81a73900-ffffffff81a73c2f: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6db30)
Location: net/ipv6/exthdrs.c:1250
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81b6db30-ffffffff81b6de5b: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7c5e0)
Location: net/ipv6/exthdrs.c:1244
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81b7c5e0-ffffffff81b7c8df: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6b1a0)
Location: net/ipv6/exthdrs.c:1244
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81b6b1a0-ffffffff81b6b49f: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c33000)
Location: net/ipv6/exthdrs.c:1292
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81c33000-ffffffff81c332ff: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dd0750)
Location: net/ipv6/exthdrs.c:1293
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81dd0750-ffffffff81dd0af6: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81fa1b20)
Location: net/ipv6/exthdrs.c:1293
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81fa1b20-ffffffff81fa1ec6: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820023a0)
Location: net/ipv6/exthdrs.c:1260
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff820023a0-ffffffff82002746: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820d11a0)
Location: net/ipv6/exthdrs.c:1265
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff820d11a0-ffffffff820d1546: ipv6_renew_options (STB_GLOBAL)
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
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffff800010d3c320)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffff800010d3c320-ffff800010d3c618: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c0e3f540)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
c0e3f540-c0e3f870: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c000000000e6ff80)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
c000000000e6ff80-c000000000e703a4: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffe000878d7a)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffe000878d7a-ffffffe000878ffc: ipv6_renew_options (STB_GLOBAL)
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
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a12f90)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81a12f90-ffffffff81a132bf: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819cfd50)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff819cfd50-ffffffff819d007f: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a7da10)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81a7da10-ffffffff81a7dd3f: ipv6_renew_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ipv6_txoptions *ipv6_renew_options(struct sock *sk, struct ipv6_txoptions *opt, int newtype, struct ipv6_opt_hdr *newopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a8a260)
Location: net/ipv6/exthdrs.c:1053
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
```
**Symbols:**

```
ffffffff81a8a260-ffffffff81a8a58f: ipv6_renew_options (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int newoptlen</code>
</li>
</ul>
</details>
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
