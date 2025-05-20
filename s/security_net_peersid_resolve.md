# Function: <code>security_net_peersid_resolve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_net_peersid_resolve(u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81359d00)
Location: security/selinux/ss/services.c:2817
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81359d00-ffffffff81359e16: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_net_peersid_resolve(u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138fcb0)
Location: security/selinux/ss/services.c:2811
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff8138fcb0-ffffffff8138fdc7: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_net_peersid_resolve(u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a68d0)
Location: security/selinux/ss/services.c:2811
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff813a68d0-ffffffff813a69e7: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_net_peersid_resolve(u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bd300)
Location: security/selinux/ss/services.c:2927
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff813bd300-ffffffff813bd414: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_net_peersid_resolve(u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e3470)
Location: security/selinux/ss/services.c:2937
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff813e3470-ffffffff813e3584: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3066
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81414dd2-ffffffff81414e12: security_net_peersid_resolve.cold.39 (STB_LOCAL)
ffffffff81413bf0-ffffffff81413d08: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff8143138d-ffffffff814313cd: security_net_peersid_resolve.cold.39 (STB_LOCAL)
ffffffff81430140-ffffffff81430256: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3051
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff8145ee58-ffffffff8145ee98: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff8145dae0-ffffffff8145dbfc: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81478c0a-ffffffff81478c4a: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff81477890-ffffffff814779ac: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3096
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff814ce0a7-ffffffff814ce0e7: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff814cccf0-ffffffff814cce28: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3224
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81bf1102-ffffffff81bf1143: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff814ea4c0-ffffffff814ea5c6: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3307
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81be3245-ffffffff81be3286: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff814f1120-ffffffff814f1226: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3315
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81cd5220-ffffffff81cd5275: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff8154b730-ffffffff8154b862: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3318
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81e88065-ffffffff81e880b2: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff815e4550-ffffffff815e4688: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3311
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff82073e94-ffffffff82073ea9: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff816938c0-ffffffff81693a20: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3256
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff820f3a45-ffffffff820f3a5a: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff816cbdc0-ffffffff816cbf1c: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3265
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff821d0c0b-ffffffff821d0c20: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff81708a80-ffffffff81708bdc: security_net_peersid_resolve (STB_GLOBAL)
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
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010567620)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffff800010567620-ffff8000105677d4: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071bb28)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
c071bb28-c071bc88: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006caaa0)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
c0000000006caaa0-c0000000006cac90: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bd2c4)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffe0003bd2c4-ffffffe0003bd3f0: security_net_peersid_resolve (STB_GLOBAL)
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
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff814711ea-ffffffff8147122a: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff8146fe70-ffffffff8146ff8c: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81461c0a-ffffffff81461c4a: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff81460890-ffffffff814609ac: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff8146d28a-ffffffff8146d2ca: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff8146bf10-ffffffff8146c02c: security_net_peersid_resolve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int security_net_peersid_resolve(struct selinux_state *state, u32 nlbl_sid, u32 nlbl_type, u32 xfrm_sid, u32 *peer_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3058
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_skb_peerlbl_sid
```
**Symbols:**

```
ffffffff81484af6-ffffffff81484b36: security_net_peersid_resolve.cold (STB_LOCAL)
ffffffff814836c0-ffffffff814837e9: security_net_peersid_resolve (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>nlbl_sid, nlbl_type, xfrm_sid, peer_sid</code> ➡️ <code>state, nlbl_sid, nlbl_type, xfrm_sid, peer_sid</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, nlbl_sid, nlbl_type, xfrm_sid, peer_sid</code> ➡️ <code>nlbl_sid, nlbl_type, xfrm_sid, peer_sid</code>
</li>
</ul>
</details>
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
