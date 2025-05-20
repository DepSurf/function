# Function: <code>__build_flow_key</code>

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
In net/ipv4/route.c (ffffffff81754cd3)
Location: net/ipv4/route.c:504
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
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
In net/ipv4/route.c (ffffffff817c2fb9)
Location: net/ipv4/route.c:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
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
In net/ipv4/route.c (ffffffff817f1696)
Location: net/ipv4/route.c:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff817efac0-ffffffff817efba6: __build_flow_key.constprop.49 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81812f46)
Location: net/ipv4/route.c:531
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff8180fa00-ffffffff8180fade: __build_flow_key.constprop.46 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81892586)
Location: net/ipv4/route.c:534
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff8188ef30-ffffffff8188f00e: __build_flow_key.constprop.46 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff818e657d)
Location: net/ipv4/route.c:517
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff818e2b20-ffffffff818e2bfb: __build_flow_key.constprop.52 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819133e2)
Location: net/ipv4/route.c:517
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff8190f9c0-ffffffff8190fa9b: __build_flow_key.constprop.55 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819759fd)
Location: net/ipv4/route.c:525
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81971b10-ffffffff81971be7: __build_flow_key.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819ac40d)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff819a85e0-ffffffff819a86b7: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81a963af)
Location: net/ipv4/route.c:525
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81a91a00-ffffffff81a91ade: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81aa044f)
Location: net/ipv4/route.c:525
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81a9b890-ffffffff81a9b96e: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8b38f)
Location: net/ipv4/route.c:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a86b90-ffffffff81a86c70: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81b462cf)
Location: net/ipv4/route.c:509
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b41350-ffffffff81b41430: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd3110)
Location: net/ipv4/route.c:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81ccdd20-ffffffff81ccde1f: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81e93276)
Location: net/ipv4/route.c:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81e8e3b0-ffffffff81e8e4a4: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef1a16)
Location: net/ipv4/route.c:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81eecad0-ffffffff81eecbc4: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb5b66)
Location: net/ipv4/route.c:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81fb0b30-ffffffff81fb0c2a: __build_flow_key.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c5c50c)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffff800010c57dc8-ffff800010c57ea0: __build_flow_key.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (c0d6bc38)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
c0d67b04-c0d67bd0: __build_flow_key.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (c000000000d5e944)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
c000000000d597c0-c000000000d598e0: __build_flow_key.isra.0.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffe0007c54ba)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffe0007c2092-ffffffe0007c2162: __build_flow_key.isra.0.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff8194c27d)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81948450-ffffffff81948527: __build_flow_key.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81905d6d)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81901f40-ffffffff81902017: __build_flow_key.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819b6a4d)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff819b2c20-ffffffff819b2cf7: __build_flow_key.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819c02bd)
Location: net/ipv4/route.c:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff819bc2e0-ffffffff819bc3b7: __build_flow_key.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
