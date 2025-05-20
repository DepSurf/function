# Function: <code>bpf_get_skb_set_tunnel_proto</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179cd30)
Location: net/core/filter.c:2263
Inline: False
Direct callers:
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff8179cd30-ffffffff8179cd85: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca650)
Location: net/core/filter.c:2517
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff817ca650-ffffffff817ca6a5: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9860)
Location: net/core/filter.c:2676
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff817e9860-ffffffff817e98b7: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864e00)
Location: net/core/filter.c:3074
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81864e00-ffffffff81864e68: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2580)
Location: net/core/filter.c:3699
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff818b2580-ffffffff818b25e8: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d7030)
Location: net/core/filter.c:3887
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff818d7030-ffffffff818d709b: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819249c0)
Location: net/core/filter.c:4024
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff819249c0-ffffffff81924a2e: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81956df0)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81956df0-ffffffff81956e5e: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ae80)
Location: net/core/filter.c:4003
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81a2ae80-ffffffff81a2aef1: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2bbb0)
Location: net/core/filter.c:4411
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81a2bbb0-ffffffff81a2bc21: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a130b0)
Location: net/core/filter.c:4350
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81a130b0-ffffffff81a13121: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac3c60)
Location: net/core/filter.c:4408
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81ac3c60-ffffffff81ac3cd1: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3edf0)
Location: net/core/filter.c:4699
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81c3edf0-ffffffff81c3ee60: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df2f30)
Location: net/core/filter.c:4717
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81df2f30-ffffffff81df2fa0: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e64db0)
Location: net/core/filter.c:4771
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81e64db0-ffffffff81e64e20: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f23f60)
Location: net/core/filter.c:4845
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81f23f60-ffffffff81f23fd0: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
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
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bffbd8)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffff800010bffbd8-ffff800010bffc94: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d179b8)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
c0d179b8-c0d17a58: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdf410)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
c000000000cdf410-c000000000cdf52c: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077a29a)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffe00077a29a-ffffffe00077a32e: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
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
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f6dc0)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff818f6dc0-ffffffff818f6e2e: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b0bf0)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff818b0bf0-ffffffff818b0c5e: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81947df0)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81947df0-ffffffff81947e5e: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_get_skb_set_tunnel_proto(enum bpf_func_id which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81969700)
Location: net/core/filter.c:4031
Inline: False
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81969700-ffffffff8196976e: bpf_get_skb_set_tunnel_proto (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
