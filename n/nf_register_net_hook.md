# Function: <code>nf_register_net_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81751090)
Location: net/netfilter/core.c:86
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81751090-ffffffff817511fc: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817bd0b0)
Location: net/netfilter/core.c:86
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff817bd0b0-ffffffff817bd22b: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817ec9f0)
Location: net/netfilter/core.c:82
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff817ec9f0-ffffffff817ecb3b: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8180d190)
Location: net/netfilter/core.c:82
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8180d190-ffffffff8180d2c9: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188c050)
Location: net/netfilter/core.c:255
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8188c050-ffffffff8188c2f8: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818e0270)
Location: net/netfilter/core.c:448
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff818e0270-ffffffff818e02f0: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190cde0)
Location: net/netfilter/core.c:448
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8190cde0-ffffffff8190ce60: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e8e0)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8196e8e0-ffffffff8196e963: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a5320)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff819a5320-ffffffff819a53a3: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8e5b7)
Location: net/netfilter/core.c:449
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81a8e4e0-ffffffff81a8e563: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a98620)
Location: net/netfilter/core.c:520
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81a98620-ffffffff81a986b3: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a83970)
Location: net/netfilter/core.c:520
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81a83970-ffffffff81a83a00: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3d730)
Location: net/netfilter/core.c:521
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81b3d730-ffffffff81b3d7c0: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc9d20)
Location: net/netfilter/core.c:551
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81cc9d20-ffffffff81cc9dbf: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e89950)
Location: net/netfilter/core.c:545
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81e89950-ffffffff81e899ef: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee7950)
Location: net/netfilter/core.c:557
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff81ee7950-ffffffff81ee79ef: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81fab760)
Location: net/netfilter/core.c:557
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff81fab760-ffffffff81fab7ff: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c548d0)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffff800010c548d0-ffff800010c5497c: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d64538)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
c0d64538-c0d645b4: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d547b0)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
c000000000d547b0-c000000000d548b8: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007beef0)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffe0007beef0-ffffffe0007bef88: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81945190)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81945190-ffffffff81945213: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fec80)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff818fec80-ffffffff818fed03: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81996320)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81996320-ffffffff819963a3: nf_register_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int nf_register_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b8ef0)
Location: net/netfilter/core.c:449
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff819b8ef0-ffffffff819b8f73: nf_register_net_hook (STB_GLOBAL)
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
