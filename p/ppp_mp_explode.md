# Function: <code>ppp_mp_explode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff815f5b5d)
Location: drivers/net/ppp/ppp_generic.c:1412
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff816558ed)
Location: drivers/net/ppp/ppp_generic.c:1625
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff816835cd)
Location: drivers/net/ppp/ppp_generic.c:1656
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff816989fd)
Location: drivers/net/ppp/ppp_generic.c:1670
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817038fd)
Location: drivers/net/ppp/ppp_generic.c:1697
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817441f1)
Location: drivers/net/ppp/ppp_generic.c:1680
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817682f1)
Location: drivers/net/ppp/ppp_generic.c:1680
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
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
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff817a5cb0-ffffffff817a618c: ppp_mp_explode.isra.0 (STB_LOCAL)
ffffffff817a7a8c-ffffffff817a7aa4: ppp_mp_explode.isra.0.cold (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff817c9700-ffffffff817c9bdc: ppp_mp_explode.isra.0 (STB_LOCAL)
ffffffff817cb4fc-ffffffff817cb514: ppp_mp_explode.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1764
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff81894890-ffffffff81894d6c: ppp_mp_explode (STB_LOCAL)
ffffffff81895b0e-ffffffff81895b26: ppp_mp_explode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1874
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff818a2fc0-ffffffff818a3491: ppp_mp_explode (STB_LOCAL)
ffffffff81c19be3-ffffffff81c19bfb: ppp_mp_explode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1907
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff81884ce0-ffffffff818851b1: ppp_mp_explode (STB_LOCAL)
ffffffff81c0b9ed-ffffffff81c0ba05: ppp_mp_explode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1912
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff819166a0-ffffffff81916b78: ppp_mp_explode (STB_LOCAL)
ffffffff81d11032-ffffffff81d11066: ppp_mp_explode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1913
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff81a68a20-ffffffff81a68f47: ppp_mp_explode (STB_LOCAL)
ffffffff81edbaf5-ffffffff81edbb3f: ppp_mp_explode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1915
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff81bfb3e0-ffffffff81bfb90e: ppp_mp_explode (STB_LOCAL)
ffffffff8209da76-ffffffff8209daa8: ppp_mp_explode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1915
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff81c60950-ffffffff81c60e98: ppp_mp_explode (STB_LOCAL)
ffffffff8211f004-ffffffff8211f030: ppp_mp_explode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1915
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff81d17320-ffffffff81d17868: ppp_mp_explode (STB_LOCAL)
ffffffff822007da-ffffffff82200806: ppp_mp_explode.cold (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (ffff800010a00688)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffff800010a00688-ffff800010a00bcc: ppp_mp_explode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ppp_mp_explode(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0adc254)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
c0adc254-c0adc7cc: ppp_mp_explode (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (c000000000aa74f0)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
c000000000aa74f0-c000000000aa7c30: ppp_mp_explode.isra.0 (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062de46)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffe00062de46-ffffffe00062e308: ppp_mp_explode.isra.0 (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff8178e1e0-ffffffff8178e6bc: ppp_mp_explode.isra.0 (STB_LOCAL)
ffffffff8178ffdc-ffffffff8178fff4: ppp_mp_explode.isra.0.cold (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff81776fb0-ffffffff8177748c: ppp_mp_explode.isra.0 (STB_LOCAL)
ffffffff81778dac-ffffffff81778dc4: ppp_mp_explode.isra.0.cold (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff817be580-ffffffff817bea5c: ppp_mp_explode.isra.0 (STB_LOCAL)
ffffffff817c037c-ffffffff817c0394: ppp_mp_explode.isra.0.cold (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1676
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
**Symbols:**

```
ffffffff817d7070-ffffffff817d753b: ppp_mp_explode.isra.0 (STB_LOCAL)
ffffffff817da5a6-ffffffff817da5be: ppp_mp_explode.isra.0.cold (STB_LOCAL)
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
