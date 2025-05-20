# Function: <code>__nf_unregister_net_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nf_hook_entry *__nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8180ce30)
Location: net/netfilter/core.c:130
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
```
**Symbols:**

```
ffffffff8180ce30-ffffffff8180cf4f: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __nf_unregister_net_hook(struct nf_hook_entries *old, const struct nf_hook_ops *unreg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188c320)
Location: net/netfilter/core.c:310
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
```
**Symbols:**

```
ffffffff8188c320-ffffffff8188c3fc: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818dfe70)
Location: net/netfilter/core.c:385
Inline: False
```
**Symbols:**

```
ffffffff818dfe70-ffffffff818dffc8: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190ca70)
Location: net/netfilter/core.c:385
Inline: False
```
**Symbols:**

```
ffffffff8190ca70-ffffffff8190cbc8: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e590)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffffffff8196e590-ffffffff8196e6bf: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a4fd0)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffffffff819a4fd0-ffffffff819a50ff: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8df50)
Location: net/netfilter/core.c:386
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81a8df50-ffffffff81a8e099: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97f60)
Location: net/netfilter/core.c:455
Inline: False
```
**Symbols:**

```
ffffffff81a97f60-ffffffff81a980e5: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a832b0)
Location: net/netfilter/core.c:455
Inline: False
```
**Symbols:**

```
ffffffff81a832b0-ffffffff81a83435: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/core.c (0)
Location: net/netfilter/core.c:456
Inline: False
```
**Symbols:**

```
ffffffff81b3cf40-ffffffff81b3d12f: __nf_unregister_net_hook (STB_LOCAL)
ffffffff81d39b64-ffffffff81d39b7f: __nf_unregister_net_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/core.c (0)
Location: net/netfilter/core.c:482
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hook
```
**Symbols:**

```
ffffffff81cc9630-ffffffff81cc9839: __nf_unregister_net_hook (STB_LOCAL)
ffffffff81f062a2-ffffffff81f062bd: __nf_unregister_net_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/core.c (0)
Location: net/netfilter/core.c:476
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hook
```
**Symbols:**

```
ffffffff81e89210-ffffffff81e8940e: __nf_unregister_net_hook (STB_LOCAL)
ffffffff820adf65-ffffffff820adf80: __nf_unregister_net_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/core.c (0)
Location: net/netfilter/core.c:488
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hook
```
**Symbols:**

```
ffffffff81ee7200-ffffffff81ee73fb: __nf_unregister_net_hook (STB_LOCAL)
ffffffff8212f46b-ffffffff8212f486: __nf_unregister_net_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/core.c (0)
Location: net/netfilter/core.c:488
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hook
```
**Symbols:**

```
ffffffff81fab010-ffffffff81fab20b: __nf_unregister_net_hook (STB_LOCAL)
ffffffff822111fc-ffffffff82211217: __nf_unregister_net_hook.cold (STB_LOCAL)
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
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c544b8)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffff800010c544b8-ffff800010c54644: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d641c0)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
c0d641c0-c0d6434c: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d542b0)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
c000000000d542b0-c000000000d544dc: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007beb98)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffffffe0007beb98-ffffffe0007becc0: __nf_unregister_net_hook (STB_LOCAL)
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
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81944e40)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffffffff81944e40-ffffffff81944f6f: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe930)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffffffff818fe930-ffffffff818fea5f: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81995fd0)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffffffff81995fd0-ffffffff819960ff: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __nf_unregister_net_hook(struct net *net, int pf, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b8ba0)
Location: net/netfilter/core.c:386
Inline: False
```
**Symbols:**

```
ffffffff819b8ba0-ffffffff819b8ccf: __nf_unregister_net_hook (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nf_hook_entries *old</code>
</li>
<li>
<b>Param added. </b>
<code>const struct nf_hook_ops *unreg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct nf_hook_ops *reg</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct nf_hook_entry *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param added. </b>
<code>int pf</code>
</li>
<li>
<b>Param added. </b>
<code>const struct nf_hook_ops *reg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nf_hook_entries *old</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct nf_hook_ops *unreg</code>
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
