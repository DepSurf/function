# Function: <code>xfrm_policy_byid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b3000)
Location: net/xfrm/xfrm_policy.c:853
Inline: True
```
**Symbols:**

```
ffffffff817b3000-ffffffff817b313a: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818207e0)
Location: net/xfrm/xfrm_policy.c:857
Inline: True
```
**Symbols:**

```
ffffffff818207e0-ffffffff8182091d: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81852020)
Location: net/xfrm/xfrm_policy.c:874
Inline: True
```
**Symbols:**

```
ffffffff81852020-ffffffff8185213d: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81875190)
Location: net/xfrm/xfrm_policy.c:869
Inline: False
```
**Symbols:**

```
ffffffff81875190-ffffffff81875295: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f6990)
Location: net/xfrm/xfrm_policy.c:840
Inline: False
```
**Symbols:**

```
ffffffff818f6990-ffffffff818f6a98: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194de40)
Location: net/xfrm/xfrm_policy.c:840
Inline: True
```
**Symbols:**

```
ffffffff8194de40-ffffffff8194df4e: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197fa60)
Location: net/xfrm/xfrm_policy.c:1700
Inline: True
```
**Symbols:**

```
ffffffff8197fa60-ffffffff8197fb70: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e96f0)
Location: net/xfrm/xfrm_policy.c:1706
Inline: True
```
**Symbols:**

```
ffffffff819e96f0-ffffffff819e9835: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a20720)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
ffffffff81a20720-ffffffff81a20865: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b12c00)
Location: net/xfrm/xfrm_policy.c:1701
Inline: True
```
**Symbols:**

```
ffffffff81b12c00-ffffffff81b12d44: xfrm_policy_byid.part.0 (STB_LOCAL)
ffffffff81b12d50-ffffffff81b12d84: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1f550)
Location: net/xfrm/xfrm_policy.c:1711
Inline: True
```
**Symbols:**

```
ffffffff81b1f550-ffffffff81b1f694: xfrm_policy_byid.part.0 (STB_LOCAL)
ffffffff81b1f6a0-ffffffff81b1f6d4: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0e5e0)
Location: net/xfrm/xfrm_policy.c:1710
Inline: True
```
**Symbols:**

```
ffffffff81b0e5e0-ffffffff81b0e76f: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd1470)
Location: net/xfrm/xfrm_policy.c:1712
Inline: True
```
**Symbols:**

```
ffffffff81bd1470-ffffffff81bd15ff: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d660c0)
Location: net/xfrm/xfrm_policy.c:1712
Inline: True
```
**Symbols:**

```
ffffffff81d660c0-ffffffff81d6622b: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f30e40)
Location: net/xfrm/xfrm_policy.c:1716
Inline: True
```
**Symbols:**

```
ffffffff81f30e40-ffffffff81f30fab: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f91b80)
Location: net/xfrm/xfrm_policy.c:1716
Inline: True
```
**Symbols:**

```
ffffffff81f91b80-ffffffff81f91ceb: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, const struct xfrm_mark *mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205f8f0)
Location: net/xfrm/xfrm_policy.c:1732
Inline: True
```
**Symbols:**

```
ffffffff8205f8f0-ffffffff8205fa5b: xfrm_policy_byid (STB_GLOBAL)
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
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdbd30)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
ffff800010cdbd30-ffff800010cdbf20: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de5640)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
c0de5640-c0de5774: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dfd5c0)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
c000000000dfd5c0-c000000000dfd790: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082a426)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
ffffffe00082a426-ffffffe00082a546: xfrm_policy_byid (STB_GLOBAL)
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
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bfdb0)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
ffffffff819bfdb0-ffffffff819bfef5: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197cba0)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
ffffffff8197cba0-ffffffff8197cce5: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2a830)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
ffffffff81a2a830-ffffffff81a2a975: xfrm_policy_byid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_byid(struct net *net, u32 mark, u32 if_id, u8 type, int dir, u32 id, int delete, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a35dd0)
Location: net/xfrm/xfrm_policy.c:1708
Inline: True
```
**Symbols:**

```
ffffffff81a35dd0-ffffffff81a35f15: xfrm_policy_byid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 if_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, mark, type, dir, id, delete, err</code> ➡️ <code>net, mark, if_id, type, dir, id, delete, err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 mark</code> ➡️ <code>const struct xfrm_mark *mark</code>
</li>
</ul>
</details>
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
