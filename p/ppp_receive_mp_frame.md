# Function: <code>ppp_receive_mp_frame</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f6dec)
Location: drivers/net/ppp/ppp_generic.c:1995
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81656f58)
Location: drivers/net/ppp/ppp_generic.c:2208
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81684c38)
Location: drivers/net/ppp/ppp_generic.c:2247
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169a068)
Location: drivers/net/ppp/ppp_generic.c:2261
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81704818)
Location: drivers/net/ppp/ppp_generic.c:2288
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81742fb8)
Location: drivers/net/ppp/ppp_generic.c:2271
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817677f5)
Location: drivers/net/ppp/ppp_generic.c:2317
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817a5015)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817c9115)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81893600)
Location: drivers/net/ppp/ppp_generic.c:2401
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81893600-ffffffff81893931: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff818a1a90)
Location: drivers/net/ppp/ppp_generic.c:2549
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff818a1a90-ffffffff818a1dc5: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81883f70)
Location: drivers/net/ppp/ppp_generic.c:2582
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81883f70-ffffffff81884297: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81915930)
Location: drivers/net/ppp/ppp_generic.c:2587
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81915930-ffffffff81915c54: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6baa0)
Location: drivers/net/ppp/ppp_generic.c:2588
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81a6baa0-ffffffff81a6bdf2: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe9c0)
Location: drivers/net/ppp/ppp_generic.c:2590
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81bfe9c0-ffffffff81bfed12: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c64020)
Location: drivers/net/ppp/ppp_generic.c:2590
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81c64020-ffffffff81c64372: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ppp_receive_mp_frame(struct ppp *ppp, struct sk_buff *skb, struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1aa40)
Location: drivers/net/ppp/ppp_generic.c:2590
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81d1aa40-ffffffff81d1ad92: ppp_receive_mp_frame (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff800010a03594)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0ade440)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aa9700)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d970)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8178dbf5)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817769c5)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817bdf95)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817d87c5)
Location: drivers/net/ppp/ppp_generic.c:2313
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
