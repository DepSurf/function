# Function: <code>xfrm_lookup_with_ifid</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3018
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81983b74-ffffffff81983b80: xfrm_lookup_with_ifid.cold.80 (STB_LOCAL)
ffffffff819821e0-ffffffff81982b4c: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3017
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff819ed88d-ffffffff819ed8bd: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff819ebed0-ffffffff819ec7d6: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81a24780-ffffffff81a2478c: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81a22ed0-ffffffff81a237e4: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3009
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81b164c3-ffffffff81b164cf: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81b151e0-ffffffff81b1566e: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3030
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81c32ab4-ffffffff81c32ac0: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81b235e0-ffffffff81b23a8d: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3029
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81c24dae-ffffffff81c24dba: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81b111e0-ffffffff81b11686: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3029
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81d3edfb-ffffffff81d3ee07: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81bd4ca0-ffffffff81bd5177: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3032
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81f0b73e-ffffffff81f0b74a: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81d6b3d0-ffffffff81d6b97c: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f366e0)
Location: net/xfrm/xfrm_policy.c:3106
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81f366e0-ffffffff81f36c98: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f960a0)
Location: net/xfrm/xfrm_policy.c:3108
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81f960a0-ffffffff81f9664a: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff82063490)
Location: net/xfrm/xfrm_policy.c:3130
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff82063490-ffffffff82063a3a: xfrm_lookup_with_ifid (STB_GLOBAL)
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
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdff68)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffff800010cdff68-ffff800010ce08a4: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de938c)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
c0de938c-c0de9ca0: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e02160)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
c000000000e02160-c000000000e02c88: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082ee72)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffe00082ee72-ffffffe00082f61c: xfrm_lookup_with_ifid (STB_GLOBAL)
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
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff819c3e10-ffffffff819c3e1c: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff819c2560-ffffffff819c2e74: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81980c00-ffffffff81980c0c: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff8197f350-ffffffff8197fc64: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81a2e890-ffffffff81a2e89c: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81a2cfe0-ffffffff81a2d8f4: xfrm_lookup_with_ifid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_with_ifid(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags, u32 if_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3019
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81a3a089-ffffffff81a3a095: xfrm_lookup_with_ifid.cold (STB_LOCAL)
ffffffff81a38720-ffffffff81a390b3: xfrm_lookup_with_ifid (STB_GLOBAL)
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
