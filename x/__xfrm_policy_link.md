# Function: <code>__xfrm_policy_link</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b0fb5)
Location: net/xfrm/xfrm_policy.c:1255
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff8181df05)
Location: net/xfrm/xfrm_policy.c:1259
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff8184f785)
Location: net/xfrm/xfrm_policy.c:1287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff81873345)
Location: net/xfrm/xfrm_policy.c:1281
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff818f5255)
Location: net/xfrm/xfrm_policy.c:1203
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff8194bd95)
Location: net/xfrm/xfrm_policy.c:1203
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff8197e5e5)
Location: net/xfrm/xfrm_policy.c:2193
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff819e8475)
Location: net/xfrm/xfrm_policy.c:2199
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff81a1f485)
Location: net/xfrm/xfrm_policy.c:2201
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b11018)
Location: net/xfrm/xfrm_policy.c:2192
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1dbc0)
Location: net/xfrm/xfrm_policy.c:2202
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffffffff81b1dbc0-ffffffff81b1dc44: __xfrm_policy_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0b560)
Location: net/xfrm/xfrm_policy.c:2201
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffffffff81b0b560-ffffffff81b0b5e4: __xfrm_policy_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bce480)
Location: net/xfrm/xfrm_policy.c:2201
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffffffff81bce480-ffffffff81bce535: __xfrm_policy_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d645b0)
Location: net/xfrm/xfrm_policy.c:2201
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffffffff81d645b0-ffffffff81d6467d: __xfrm_policy_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2f2c0)
Location: net/xfrm/xfrm_policy.c:2274
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffffffff81f2f2c0-ffffffff81f2f38d: __xfrm_policy_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8fac0)
Location: net/xfrm/xfrm_policy.c:2276
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffffffff81f8fac0-ffffffff81f8fb8d: __xfrm_policy_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205d820)
Location: net/xfrm/xfrm_policy.c:2296
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffffffff8205d820-ffffffff8205d8ed: __xfrm_policy_link (STB_LOCAL)
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
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cd9188)
Location: net/xfrm/xfrm_policy.c:2201
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
ffff800010cd9188-ffff800010cd91e8: __xfrm_policy_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __xfrm_policy_link(struct xfrm_policy *pol, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de28bc)
Location: net/xfrm/xfrm_policy.c:2201
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
**Symbols:**

```
c0de28bc-c0de2918: __xfrm_policy_link (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (c000000000e040b0)
Location: net/xfrm/xfrm_policy.c:2201
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffe0008302a6)
Location: net/xfrm/xfrm_policy.c:2201
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff819beb15)
Location: net/xfrm/xfrm_policy.c:2201
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff8197b905)
Location: net/xfrm/xfrm_policy.c:2201
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff81a29595)
Location: net/xfrm/xfrm_policy.c:2201
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In net/xfrm/xfrm_policy.c (ffffffff81a34b25)
Location: net/xfrm/xfrm_policy.c:2201
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
