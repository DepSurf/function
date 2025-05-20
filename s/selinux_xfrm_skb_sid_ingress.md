# Function: <code>selinux_xfrm_skb_sid_ingress</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/xfrm.c (ffffffff8135cde0)
Location: security/selinux/xfrm.c:224
Inline: True
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
**Symbols:**

```
ffffffff8135cde0-ffffffff8135ce4f: selinux_xfrm_skb_sid_ingress.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/xfrm.c (ffffffff81392da0)
Location: security/selinux/xfrm.c:224
Inline: True
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff81392da0-ffffffff81392e16: selinux_xfrm_skb_sid_ingress.isra.1 (STB_LOCAL)
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
In security/selinux/xfrm.c (ffffffff813a99c0)
Location: security/selinux/xfrm.c:224
Inline: True
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff813a99c0-ffffffff813a9a36: selinux_xfrm_skb_sid_ingress.isra.1 (STB_LOCAL)
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
In security/selinux/xfrm.c (ffffffff813c0380)
Location: security/selinux/xfrm.c:224
Inline: True
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff813c0380-ffffffff813c0406: selinux_xfrm_skb_sid_ingress.isra.2 (STB_LOCAL)
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
In security/selinux/xfrm.c (ffffffff813e6520)
Location: security/selinux/xfrm.c:224
Inline: True
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff813e6520-ffffffff813e65a6: selinux_xfrm_skb_sid_ingress.isra.2 (STB_LOCAL)
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
In security/selinux/xfrm.c (ffffffff81417240)
Location: security/selinux/xfrm.c:229
Inline: True
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff81417240-ffffffff814172c6: selinux_xfrm_skb_sid_ingress.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff81433780)
Location: security/selinux/xfrm.c:229
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff81433780-ffffffff81433815: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff814611f0)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff814611f0-ffffffff81461284: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff8147afa0)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff8147afa0-ffffffff8147b034: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff814d04d0)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff814d04d0-ffffffff814d0566: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff814ed9e0)
Location: security/selinux/xfrm.c:227
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff814ed9e0-ffffffff814eda76: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff814f4760)
Location: security/selinux/xfrm.c:227
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff814f4760-ffffffff814f47ee: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff8154f110)
Location: security/selinux/xfrm.c:227
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff8154f110-ffffffff8154f1ca: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff815e82a0)
Location: security/selinux/xfrm.c:227
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff815e82a0-ffffffff815e8364: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff81697a00)
Location: security/selinux/xfrm.c:227
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff81697a00-ffffffff81697ac4: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff816cff00)
Location: security/selinux/xfrm.c:224
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff816cff00-ffffffff816cffc4: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff8170c520)
Location: security/selinux/xfrm.c:224
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff8170c520-ffffffff8170c5e4: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
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
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffff80001056b4a8)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffff80001056b4a8-ffff80001056b570: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (c071f0e4)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
c071f0e4-c071f1a0: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (c0000000006cf600)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
c0000000006cf600-c0000000006cf6dc: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffe0003c0468)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffe0003c0468-ffffffe0003c0508: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
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
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff81473580)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff81473580-ffffffff81473614: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff81463fa0)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff81463fa0-ffffffff81464034: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff8146f620)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff8146f620-ffffffff8146f6b4: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_xfrm_skb_sid_ingress(struct sk_buff *skb, u32 *sid, int ckall);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff81486e90)
Location: security/selinux/xfrm.c:226
Inline: False
Direct callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_decode_session
```
**Symbols:**

```
ffffffff81486e90-ffffffff81486f24: selinux_xfrm_skb_sid_ingress (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
