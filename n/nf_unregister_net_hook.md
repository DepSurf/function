# Function: <code>nf_unregister_net_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81751220)
Location: net/netfilter/core.c:123
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
  - net/netfilter/core.c:nf_unregister_hook
  - net/netfilter/core.c:netfilter_net_exit
```
**Symbols:**

```
ffffffff81751220-ffffffff8175136b: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817bd250)
Location: net/netfilter/core.c:123
Inline: False
Direct callers:
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/core.c:nf_unregister_hook
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff817bd250-ffffffff817bd39d: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817ecb60)
Location: net/netfilter/core.c:129
Inline: False
Direct callers:
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/core.c:_nf_unregister_hook
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff817ecb60-ffffffff817eccc8: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8180cf50)
Location: net/netfilter/core.c:162
Inline: False
```
**Symbols:**

```
ffffffff8180cf50-ffffffff8180cf91: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188c400)
Location: net/netfilter/core.c:340
Inline: False
```
**Symbols:**

```
ffffffff8188c400-ffffffff8188c4ce: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818e01e0)
Location: net/netfilter/core.c:424
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff818e01e0-ffffffff818e0228: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190cd50)
Location: net/netfilter/core.c:424
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8190cd50-ffffffff8190cd98: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e840)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8196e840-ffffffff8196e893: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a5280)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff819a5280-ffffffff819a52d3: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8e127)
Location: net/netfilter/core.c:425
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
```
**Symbols:**

```
ffffffff81a8e0a0-ffffffff81a8e0ef: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a980f0)
Location: net/netfilter/core.c:492
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81a980f0-ffffffff81a98157: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a83440)
Location: net/netfilter/core.c:492
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81a83440-ffffffff81a834a7: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3d130)
Location: net/netfilter/core.c:493
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81b3d130-ffffffff81b3d197: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc9840)
Location: net/netfilter/core.c:523
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81cc9840-ffffffff81cc98c2: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e89420)
Location: net/netfilter/core.c:517
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81e89420-ffffffff81e894a2: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee7410)
Location: net/netfilter/core.c:529
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_detach
```
**Symbols:**

```
ffffffff81ee7410-ffffffff81ee7492: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81fab220)
Location: net/netfilter/core.c:529
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_detach
```
**Symbols:**

```
ffffffff81fab220-ffffffff81fab2a2: nf_unregister_net_hook (STB_GLOBAL)
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
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c54808)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffff800010c54808-ffff800010c54870: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d644a0)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
c0d644a0-c0d644f0: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d546b0)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
c000000000d546b0-c000000000d54720: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007bee32)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffe0007bee32-ffffffe0007bee96: nf_unregister_net_hook (STB_GLOBAL)
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
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819450f0)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff819450f0-ffffffff81945143: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818febe0)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff818febe0-ffffffff818fec33: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81996280)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81996280-ffffffff819962d3: nf_unregister_net_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hook(struct net *net, const struct nf_hook_ops *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b8e50)
Location: net/netfilter/core.c:425
Inline: True
Direct callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff819b8e50-ffffffff819b8ea3: nf_unregister_net_hook (STB_GLOBAL)
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
