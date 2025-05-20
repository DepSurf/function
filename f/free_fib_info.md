# Function: <code>free_fib_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179c3b0)
Location: net/ipv4/fib_semantics.c:222
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff8179c3b0-ffffffff8179c414: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81809f30)
Location: net/ipv4/fib_semantics.c:222
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81809f30-ffffffff81809f94: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183aba0)
Location: net/ipv4/fib_semantics.c:222
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff8183aba0-ffffffff8183ac04: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185c210)
Location: net/ipv4/fib_semantics.c:227
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff8185c210-ffffffff8185c274: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818dc100)
Location: net/ipv4/fib_semantics.c:228
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff818dc100-ffffffff818dc164: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:228
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81935772-ffffffff81935786: free_fib_info.cold.27 (STB_LOCAL)
ffffffff81932d40-ffffffff81932d97: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:226
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81965172-ffffffff81965186: free_fib_info.cold.27 (STB_LOCAL)
ffffffff819625d0-ffffffff81962627: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff819cb05e-ffffffff819cb072: free_fib_info.cold (STB_LOCAL)
ffffffff819c7340-ffffffff819c736c: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81a01c65-ffffffff81a01c79: free_fib_info.cold (STB_LOCAL)
ffffffff819fdef0-ffffffff819fdf1c: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aef2a6)
Location: net/ipv4/fib_semantics.c:248
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81af09ce-ffffffff81af09e2: free_fib_info.cold (STB_LOCAL)
ffffffff81aec9e0-ffffffff81aeca0c: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afc1ef)
Location: net/ipv4/fib_semantics.c:248
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81c329cf-ffffffff81c329e3: free_fib_info.cold (STB_LOCAL)
ffffffff81af98c0-ffffffff81af98ec: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae7904)
Location: net/ipv4/fib_semantics.c:248
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81c24ca3-ffffffff81c24cb7: free_fib_info.cold (STB_LOCAL)
ffffffff81ae4fc0-ffffffff81ae4fec: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba782c)
Location: net/ipv4/fib_semantics.c:247
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81d3c850-ffffffff81d3c864: free_fib_info.cold (STB_LOCAL)
ffffffff81ba48f0-ffffffff81ba4915: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81d3a05c)
Location: net/ipv4/fib_semantics.c:249
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81f090d9-ffffffff81f090ed: free_fib_info.cold (STB_LOCAL)
ffffffff81d377f0-ffffffff81d3781f: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f029bc)
Location: net/ipv4/fib_semantics.c:250
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81effe00-ffffffff81effe46: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f624bc)
Location: net/ipv4/fib_semantics.c:250
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81f5f880-ffffffff81f5f8c6: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff82028a8c)
Location: net/ipv4/fib_semantics.c:250
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff82025e50-ffffffff82025e96: free_fib_info (STB_GLOBAL)
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
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb6018)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffff800010cb6018-ffff800010cb6078: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc1af8)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
c0dc1af8-c0dc1b54: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dcdeb0)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
c000000000dcdeb0-c000000000dcdf24: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080d82c)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffe00080d82c-ffffffe00080d888: free_fib_info (STB_GLOBAL)
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
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff819a1a05-ffffffff819a1a19: free_fib_info.cold (STB_LOCAL)
ffffffff8199dc90-ffffffff8199dcbc: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff8195b4c5-ffffffff8195b4d9: free_fib_info.cold (STB_LOCAL)
ffffffff81957750-ffffffff8195777c: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81a0c2a5-ffffffff81a0c2b9: free_fib_info.cold (STB_LOCAL)
ffffffff81a08530-ffffffff81a0855c: free_fib_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void free_fib_info(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:248
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
**Symbols:**

```
ffffffff81a16a95-ffffffff81a16aa9: free_fib_info.cold (STB_LOCAL)
ffffffff81a12c80-ffffffff81a12cac: free_fib_info (STB_GLOBAL)
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
