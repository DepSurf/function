# Function: <code>netlbl_mgmt_listentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d660)
Location: net/netlabel/netlabel_mgmt.c:263
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff8180d660-ffffffff8180da19: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fa60)
Location: net/netlabel/netlabel_mgmt.c:300
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff8187fa60-ffffffff8187fec8: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4310)
Location: net/netlabel/netlabel_mgmt.c:294
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff818b4310-ffffffff818b4778: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff818dacc0)
Location: net/netlabel/netlabel_mgmt.c:294
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff818dacc0-ffffffff818db10a: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff819608a0)
Location: net/netlabel/netlabel_mgmt.c:294
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff819608a0-ffffffff81960cea: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba060)
Location: net/netlabel/netlabel_mgmt.c:294
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff819ba060-ffffffff819ba4d3: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff819f19b0)
Location: net/netlabel/netlabel_mgmt.c:294
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff819f19b0-ffffffff819f1e23: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81a605f0)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81a605f0-ffffffff81a609ed: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffffffff81a61080-ffffffff81a6111e: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97220)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81a97220-ffffffff81a9761d: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffffffff81a97cb0-ffffffff81a97d4e: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93210)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81b93210-ffffffff81b9366a: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2e60)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81ba2e60-ffffffff81ba32ba: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91f80)
Location: net/netlabel/netlabel_mgmt.c:281
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81b91f80-ffffffff81b923da: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e720)
Location: net/netlabel/netlabel_mgmt.c:281
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81c5e720-ffffffff81c5eb7a: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00940)
Location: net/netlabel/netlabel_mgmt.c:281
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81e00940-ffffffff81e00dac: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5790)
Location: net/netlabel/netlabel_mgmt.c:281
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81fd5790-ffffffff81fd5bfc: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff82051430)
Location: net/netlabel/netlabel_mgmt.c:281
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff82051430-ffffffff820518bb: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff82123c00)
Location: net/netlabel/netlabel_mgmt.c:281
Inline: False
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff82123c00-ffffffff8212408b: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffff800010d66800)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffff800010d66800-ffff800010d66c2c: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffff800010d67268-ffff800010d67314: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (c0e64f14)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
c0e64f14-c0e6530c: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
c0e65868-c0e65920: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (c000000000ea2a30)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
c000000000ea2a30-c000000000ea2f88: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
c000000000ea2f90-c000000000ea3078: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a236)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffe00089a236-ffffffe00089a548: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffffffe00089aa56-ffffffe00089aace: netlbl_mgmt_listentry (STB_LOCAL)
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
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81a365b0)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81a365b0-ffffffff81a369ad: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffffffff81a37040-ffffffff81a370de: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff819f31d0)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff819f31d0-ffffffff819f35cd: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffffffff819f3c60-ffffffff819f3cfe: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2460)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81aa2460-ffffffff81aa285d: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffffffff81aa2ef0-ffffffff81aa2f8e: netlbl_mgmt_listentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_mgmt_listentry(struct sk_buff *skb, struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae7d0)
Location: net/netlabel/netlabel_mgmt.c:280
Inline: True
Direct callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
**Symbols:**

```
ffffffff81aae7d0-ffffffff81aaebcd: netlbl_mgmt_listentry.part.0 (STB_LOCAL)
ffffffff81aaf260-ffffffff81aaf2fe: netlbl_mgmt_listentry (STB_LOCAL)
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
