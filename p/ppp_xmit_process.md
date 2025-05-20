# Function: <code>ppp_xmit_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ppp_xmit_process(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff815f7830)
Location: drivers/net/ppp/ppp_generic.c:1162
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff815f7830-ffffffff815f7e1d: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ppp_xmit_process(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff816579d0)
Location: drivers/net/ppp/ppp_generic.c:1375
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff816579d0-ffffffff81657ff8: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81685df0)
Location: drivers/net/ppp/ppp_generic.c:1404
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81685df0-ffffffff81685e69: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8169b200)
Location: drivers/net/ppp/ppp_generic.c:1418
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff8169b200-ffffffff8169b295: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817059f0)
Location: drivers/net/ppp/ppp_generic.c:1443
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff817059f0-ffffffff81705a94: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81744ea0)
Location: drivers/net/ppp/ppp_generic.c:1426
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81744ea0-ffffffff81744f44: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81768f90)
Location: drivers/net/ppp/ppp_generic.c:1426
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81768f90-ffffffff81769034: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817a7b2b)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff817a6a70-ffffffff817a6b04: ppp_xmit_process (STB_LOCAL)
ffffffff817a7b2b-ffffffff817a7b43: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817cb59b)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff817ca4d0-ffffffff817ca564: ppp_xmit_process (STB_LOCAL)
ffffffff817cb59b-ffffffff817cb5b3: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1510
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81895520-ffffffff818955b4: ppp_xmit_process (STB_LOCAL)
ffffffff81895b78-ffffffff81895b90: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1620
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff818a3c50-ffffffff818a3ce4: ppp_xmit_process (STB_LOCAL)
ffffffff81c19c4d-ffffffff81c19c65: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1653
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81885960-ffffffff818859f4: ppp_xmit_process (STB_LOCAL)
ffffffff81c0ba57-ffffffff81c0ba6f: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1658
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff819172f0-ffffffff81917384: ppp_xmit_process (STB_LOCAL)
ffffffff81d110b8-ffffffff81d110d0: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1659
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81a6b6f0-ffffffff81a6b78d: ppp_xmit_process (STB_LOCAL)
ffffffff81edbddf-ffffffff81edbdf7: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe5d0)
Location: drivers/net/ppp/ppp_generic.c:1659
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81bfe5d0-ffffffff81bfe67d: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63c10)
Location: drivers/net/ppp/ppp_generic.c:1659
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81c63c10-ffffffff81c63cbd: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a630)
Location: drivers/net/ppp/ppp_generic.c:1659
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81d1a630-ffffffff81d1a6dd: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff800010a02130)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffff800010a02130-ffff800010a021e4: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0adf250)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
c0adf250-c0adf304: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aaaad0)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
c000000000aaaad0-c000000000aaabcc: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062eb80)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffe00062eb80-ffffffe00062ec4c: ppp_xmit_process (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8179007b)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff8178efb0-ffffffff8178f044: ppp_xmit_process (STB_LOCAL)
ffffffff8179007b-ffffffff81790093: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81778e4b)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff81777d80-ffffffff81777e14: ppp_xmit_process (STB_LOCAL)
ffffffff81778e4b-ffffffff81778e63: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817c041b)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff817bf350-ffffffff817bf3e4: ppp_xmit_process (STB_LOCAL)
ffffffff817c041b-ffffffff817c0433: ppp_xmit_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ppp_xmit_process(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817da6ce)
Location: drivers/net/ppp/ppp_generic.c:1422
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
**Symbols:**

```
ffffffff817d95e0-ffffffff817d9674: ppp_xmit_process (STB_LOCAL)
ffffffff817da6ce-ffffffff817da6e6: ppp_xmit_process.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff *skb</code>
</li>
</ul>
</details>
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
