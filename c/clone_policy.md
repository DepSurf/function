# Function: <code>clone_policy</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b69c4)
Location: net/xfrm/xfrm_policy.c:1345
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
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
In net/xfrm/xfrm_policy.c (ffffffff818239e4)
Location: net/xfrm/xfrm_policy.c:1349
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81855334)
Location: net/xfrm/xfrm_policy.c:1377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
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
In net/xfrm/xfrm_policy.c (ffffffff81878ed8)
Location: net/xfrm/xfrm_policy.c:1371
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f9818)
Location: net/xfrm/xfrm_policy.c:1293
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81950288)
Location: net/xfrm/xfrm_policy.c:1293
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81983938)
Location: net/xfrm/xfrm_policy.c:2284
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819ed518)
Location: net/xfrm/xfrm_policy.c:2290
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a24528)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b10e20)
Location: net/xfrm/xfrm_policy.c:2283
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff81b10e20-ffffffff81b110e8: clone_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1edd0)
Location: net/xfrm/xfrm_policy.c:2293
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff81b1edd0-ffffffff81b1f028: clone_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0ca50)
Location: net/xfrm/xfrm_policy.c:2292
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff81b0ca50-ffffffff81b0cca8: clone_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bcfc40)
Location: net/xfrm/xfrm_policy.c:2292
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff81bcfc40-ffffffff81bcfe98: clone_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d65cd0)
Location: net/xfrm/xfrm_policy.c:2292
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff81d65cd0-ffffffff81d65f39: clone_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:2366
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff81f31210-ffffffff81f314c7: clone_policy (STB_LOCAL)
ffffffff820b2f11-ffffffff820b2f34: clone_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:2368
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff81f91d00-ffffffff81f91fb7: clone_policy (STB_LOCAL)
ffffffff8213412a-ffffffff8213414d: clone_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct xfrm_policy *clone_policy(const struct xfrm_policy *old, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:2388
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
**Symbols:**

```
ffffffff8205fa70-ffffffff8205fd27: clone_policy (STB_LOCAL)
ffffffff82215d30-ffffffff82215d53: clone_policy.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010ce17d0)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0deab2c)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e03f6c)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe000830296)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c3bb8)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819809a8)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2e638)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a39e2e)
Location: net/xfrm/xfrm_policy.c:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
