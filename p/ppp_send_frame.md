# Function: <code>ppp_send_frame</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f78ac)
Location: drivers/net/ppp/ppp_generic.c:1238
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff81657a4c)
Location: drivers/net/ppp/ppp_generic.c:1451
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff8168572c)
Location: drivers/net/ppp/ppp_generic.c:1482
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169ab3b)
Location: drivers/net/ppp/ppp_generic.c:1496
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff8170532d)
Location: drivers/net/ppp/ppp_generic.c:1523
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff817447dd)
Location: drivers/net/ppp/ppp_generic.c:1506
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
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
In drivers/net/ppp/ppp_generic.c (ffffffff817688dd)
Location: drivers/net/ppp/ppp_generic.c:1506
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff817a6250-ffffffff817a6824: ppp_send_frame (STB_LOCAL)
ffffffff817a7aa4-ffffffff817a7b2b: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff817c9ca0-ffffffff817ca274: ppp_send_frame (STB_LOCAL)
ffffffff817cb514-ffffffff817cb59b: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1590
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81894e30-ffffffff818952c1: ppp_send_frame (STB_LOCAL)
ffffffff81895b26-ffffffff81895b78: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1700
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff818a3560-ffffffff818a39f1: ppp_send_frame (STB_LOCAL)
ffffffff81c19bfb-ffffffff81c19c4d: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1733
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81885280-ffffffff81885703: ppp_send_frame (STB_LOCAL)
ffffffff81c0ba05-ffffffff81c0ba57: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1738
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81916c40-ffffffff81917093: ppp_send_frame (STB_LOCAL)
ffffffff81d11066-ffffffff81d110b8: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1739
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81a6b000-ffffffff81a6b45b: ppp_send_frame (STB_LOCAL)
ffffffff81edbd90-ffffffff81edbddf: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfde40)
Location: drivers/net/ppp/ppp_generic.c:1739
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81bfde40-ffffffff81bfe2ee: ppp_send_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63480)
Location: drivers/net/ppp/ppp_generic.c:1739
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81c63480-ffffffff81c6393a: ppp_send_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19ea0)
Location: drivers/net/ppp/ppp_generic.c:1739
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81d19ea0-ffffffff81d1a35a: ppp_send_frame (STB_LOCAL)
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
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff800010a017b8)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffff800010a017b8-ffff800010a01d54: ppp_send_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0ade9a8)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
c0ade9a8-c0adeff8: ppp_send_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aa9f60)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
c000000000aa9f60-c000000000aaa6d0: ppp_send_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062e3ec)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffe00062e3ec-ffffffe00062e91e: ppp_send_frame (STB_LOCAL)
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
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff8178e780-ffffffff8178ed54: ppp_send_frame (STB_LOCAL)
ffffffff8178fff4-ffffffff8179007b: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81777550-ffffffff81777b24: ppp_send_frame (STB_LOCAL)
ffffffff81778dc4-ffffffff81778e4b: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff817beb20-ffffffff817bf0f4: ppp_send_frame (STB_LOCAL)
ffffffff817c0394-ffffffff817c041b: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ppp_send_frame(struct ppp *ppp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:1502
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff817d8db0-ffffffff817d9384: ppp_send_frame (STB_LOCAL)
ffffffff817da647-ffffffff817da6ce: ppp_send_frame.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
