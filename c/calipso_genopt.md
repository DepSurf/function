# Function: <code>calipso_genopt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8186f8e0)
Location: net/ipv6/calipso.c:741
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff8186f8e0-ffffffff8186fa64: calipso_genopt.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a2850)
Location: net/ipv6/calipso.c:741
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff818a2850-ffffffff818a29d4: calipso_genopt.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818c8e10)
Location: net/ipv6/calipso.c:741
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff818c8e10-ffffffff818c8f88: calipso_genopt.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194c4b0)
Location: net/ipv6/calipso.c:741
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff8194c4b0-ffffffff8194c628: calipso_genopt.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a5510)
Location: net/ipv6/calipso.c:741
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff819a5510-ffffffff819a568f: calipso_genopt.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dbfa0)
Location: net/ipv6/calipso.c:741
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff819dbfa0-ffffffff819dc11f: calipso_genopt.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4ac20)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81a4ac20-ffffffff81a4ad9c: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a817f0)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81a817f0-ffffffff81a8196c: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7c710)
Location: net/ipv6/calipso.c:727
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81b7c710-ffffffff81b7c88b: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8b750)
Location: net/ipv6/calipso.c:723
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81b8b750-ffffffff81b8b8cb: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7a5a0)
Location: net/ipv6/calipso.c:723
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81b7a5a0-ffffffff81b7a716: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81c45260)
Location: net/ipv6/calipso.c:723
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81c45260-ffffffff81c453d6: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81de4300)
Location: net/ipv6/calipso.c:723
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81de4300-ffffffff81de449f: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81fb6a30)
Location: net/ipv6/calipso.c:723
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81fb6a30-ffffffff81fb6bcf: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff82017130)
Location: net/ipv6/calipso.c:723
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff82017130-ffffffff820172cf: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820e60d0)
Location: net/ipv6/calipso.c:723
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff820e60d0-ffffffff820e626f: calipso_genopt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4cf78)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffff800010d4cf78-ffff800010d4d114: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int calipso_genopt(unsigned char *buf, u32 start, u32 buf_len, const struct calipso_doi *doi_def, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4e5e8)
Location: net/ipv6/calipso.c:727
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
c0e4e5e8-c0e4e764: calipso_genopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (c000000000e83ec0)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
c000000000e83ec0-c000000000e8412c: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffe000885e08)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffe000885e08-ffffffe000885fa0: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a20e80)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81a20e80-ffffffff81a20ffc: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819ddc40)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff819ddc40-ffffffff819dddbc: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8b900)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81a8b900-ffffffff81a8ba7c: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a98790)
Location: net/ipv6/calipso.c:727
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_opt_insert
```
**Symbols:**

```
ffffffff81a98790-ffffffff81a9890c: calipso_genopt.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
