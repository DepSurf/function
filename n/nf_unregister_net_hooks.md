# Function: <code>nf_unregister_net_hooks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81751370)
Location: net/netfilter/core.c:181
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81751370-ffffffff817513ba: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817bd43d)
Location: net/netfilter/core.c:181
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff817bd3a0-ffffffff817bd3e4: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817ecd6d)
Location: net/netfilter/core.c:185
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff817eccd0-ffffffff817ecd14: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8180cfa0)
Location: net/netfilter/core.c:200
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8180cfa0-ffffffff8180d0a3: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188c4d0)
Location: net/netfilter/core.c:395
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff8188c4d0-ffffffff8188c712: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818e0351)
Location: net/netfilter/core.c:492
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffff818e0230-ffffffff818e0270: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190cec1)
Location: net/netfilter/core.c:492
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffff8190cda0-ffffffff8190cde0: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e9d5)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffff8196e8a0-ffffffff8196e8e0: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a5415)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffff819a52e0-ffffffff819a5320: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8e0f0)
Location: net/netfilter/core.c:493
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
  - net/netfilter/core.c:nf_register_net_hooks
```
**Symbols:**

```
ffffffff81a8e0f0-ffffffff81a8e162: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a98722)
Location: net/netfilter/core.c:570
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
```
**Symbols:**

```
ffffffff81a98320-ffffffff81a983a7: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a83a62)
Location: net/netfilter/core.c:570
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
```
**Symbols:**

```
ffffffff81a83670-ffffffff81a836f7: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3d822)
Location: net/netfilter/core.c:571
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
```
**Symbols:**

```
ffffffff81b3d360-ffffffff81b3d3e7: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc9e1b)
Location: net/netfilter/core.c:601
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
```
**Symbols:**

```
ffffffff81cc98d0-ffffffff81cc9971: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e89a5b)
Location: net/netfilter/core.c:595
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
```
**Symbols:**

```
ffffffff81e894c0-ffffffff81e89561: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee7a5b)
Location: net/netfilter/core.c:607
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
```
**Symbols:**

```
ffffffff81ee74b0-ffffffff81ee7551: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81fab86b)
Location: net/netfilter/core.c:607
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/apparmor/lsm.c:apparmor_nf_unregister
```
**Symbols:**

```
ffffffff81fab2c0-ffffffff81fab361: nf_unregister_net_hooks (STB_GLOBAL)
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
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c549f8)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffff800010c54870-ffff800010c548d0: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d6461c)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
c0d644f0-c0d64538: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d54720)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
c000000000d54720-c000000000d547a4: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007befee)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffe0007bee96-ffffffe0007beef0: nf_unregister_net_hooks (STB_GLOBAL)
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
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81945285)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffff81945150-ffffffff81945190: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fed75)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffff818fec40-ffffffff818fec80: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81996415)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
  - net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_put
  - net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_put
  - net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_put
```
**Symbols:**

```
ffffffff819962e0-ffffffff81996320: nf_unregister_net_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nf_unregister_net_hooks(struct net *net, const struct nf_hook_ops *reg, unsigned int hookcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b8fe5)
Location: net/netfilter/core.c:493
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hooks
Direct callers:
  - security/selinux/hooks.c:selinux_nf_unregister
  - security/smack/smack_netfilter.c:smack_nf_unregister
```
**Symbols:**

```
ffffffff819b8eb0-ffffffff819b8ef0: nf_unregister_net_hooks (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int hookcount</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int n</code>
</li>
</ul>
</details>
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
