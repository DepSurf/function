# Function: <code>rtnl_net_fill</code>

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
In net/core/net_namespace.c (ffffffff8170fda0)
Location: net/core/net_namespace.c:591
Inline: True
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff8170fda0-ffffffff8170fe98: rtnl_net_fill.isra.5 (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff817776e0)
Location: net/core/net_namespace.c:591
Inline: True
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff817776e0-ffffffff817777d8: rtnl_net_fill.isra.5 (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff817a4760)
Location: net/core/net_namespace.c:621
Inline: True
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff817a4760-ffffffff817a4858: rtnl_net_fill.isra.7 (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff817c28a0)
Location: net/core/net_namespace.c:678
Inline: True
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff817c28a0-ffffffff817c2982: rtnl_net_fill.isra.6 (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff8183c1e0)
Location: net/core/net_namespace.c:679
Inline: True
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff8183c1e0-ffffffff8183c2c2: rtnl_net_fill.isra.6 (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff81886c40)
Location: net/core/net_namespace.c:741
Inline: True
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81886c40-ffffffff81886d22: rtnl_net_fill.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a7330)
Location: net/core/net_namespace.c:753
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff818a7330-ffffffff818a744b: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (0)
Location: net/core/net_namespace.c:797
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff818f23d0-ffffffff818f24eb: rtnl_net_fill (STB_LOCAL)
ffffffff818f40d8-ffffffff818f40f3: rtnl_net_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81924320)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81924320-ffffffff8192443b: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f7ff0)
Location: net/core/net_namespace.c:807
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff819f7ff0-ffffffff819f810b: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f7a50)
Location: net/core/net_namespace.c:808
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff819f7a50-ffffffff819f7b6b: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819ddbd0)
Location: net/core/net_namespace.c:805
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff819ddbd0-ffffffff819ddcea: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (0)
Location: net/core/net_namespace.c:807
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81a8de50-ffffffff81a8df7d: rtnl_net_fill (STB_LOCAL)
ffffffff81d355fd-ffffffff81d35612: rtnl_net_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (0)
Location: net/core/net_namespace.c:807
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81c03ab0-ffffffff81c03bef: rtnl_net_fill (STB_LOCAL)
ffffffff81f01b68-ffffffff81f01b7d: rtnl_net_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (0)
Location: net/core/net_namespace.c:826
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81db3160-ffffffff81db329f: rtnl_net_fill (STB_LOCAL)
ffffffff820aafa8-ffffffff820aafbd: rtnl_net_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (0)
Location: net/core/net_namespace.c:825
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81e23730-ffffffff81e2386f: rtnl_net_fill (STB_LOCAL)
ffffffff8212c600-ffffffff8212c615: rtnl_net_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (0)
Location: net/core/net_namespace.c:829
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81ee1690-ffffffff81ee17cf: rtnl_net_fill (STB_LOCAL)
ffffffff8220e325-ffffffff8220e33a: rtnl_net_fill.cold (STB_LOCAL)
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
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bbfc60)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffff800010bbfc60-ffff800010bbfd90: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdb758)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
c0cdb758-c0cdb8a0: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c990a0)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
c000000000c990a0-c000000000c9924c: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074d56c)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffe00074d56c-ffffffe00074d63e: rtnl_net_fill (STB_LOCAL)
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
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c4320)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff818c4320-ffffffff818c443b: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187e260)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff8187e260-ffffffff8187e37b: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81915320)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81915320-ffffffff8191543b: rtnl_net_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtnl_net_fill(struct sk_buff *skb, struct net_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81936500)
Location: net/core/net_namespace.c:801
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff81936500-ffffffff8193661b: rtnl_net_fill (STB_LOCAL)
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
