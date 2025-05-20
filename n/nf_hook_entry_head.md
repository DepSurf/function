# Function: <code>nf_hook_entry_head</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817ecb7d)
Location: net/netfilter/core.c:68
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_register_net_hook
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
In net/netfilter/core.c (ffffffff8180ce45)
Location: net/netfilter/core.c:68
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:nf_register_net_hook
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
In net/netfilter/core.c (ffffffff8188c525)
Location: net/netfilter/core.c:240
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
```
**Symbols:**

```
ffffffff8188c040-ffffffff8188c04f: nf_hook_entry_head.isra.4.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818df760)
Location: net/netfilter/core.c:266
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff818df760-ffffffff818df811: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c2c0)
Location: net/netfilter/core.c:266
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff8190c2c0-ffffffff8190c37b: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196de80)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff8196de80-ffffffff8196df3b: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a4930)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819a4930-ffffffff819a49eb: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8d9d0)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81a8d9d0-ffffffff81a8da8b: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97960)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81a97960-ffffffff81a97a5f: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a82cb0)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81a82cb0-ffffffff81a82daf: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3c900)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81b3c900-ffffffff81b3c9ff: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc8c50)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81cc8c50-ffffffff81cc8e02: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e887d0)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81e887d0-ffffffff81e88958: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee6780)
Location: net/netfilter/core.c:279
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81ee6780-ffffffff81ee68ee: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81faa530)
Location: net/netfilter/core.c:279
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81faa530-ffffffff81faa69e: nf_hook_entry_head (STB_LOCAL)
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
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c53ca8)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffff800010c53ca8-ffff800010c53de0: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d63a9c)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
c0d63a9c-c0d63d34: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d53a10)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
c000000000d53a10-c000000000d53b68: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007be482)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffe0007be482-ffffffe0007be5f0: nf_hook_entry_head (STB_LOCAL)
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
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819447a0)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819447a0-ffffffff8194485b: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe290)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff818fe290-ffffffff818fe34b: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81995930)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81995930-ffffffff819959eb: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nf_hook_entries **nf_hook_entry_head(struct net *net, int pf, unsigned int hooknum, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b8510)
Location: net/netfilter/core.c:267
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819b8510-ffffffff819b85cb: nf_hook_entry_head (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
