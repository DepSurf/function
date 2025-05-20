# Function: <code>xfrm_flowi_sport</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (ffffffff817afc85)
Location: include/net/xfrm.h:858
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b49cb)
Location: include/net/xfrm.h:858
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/ipv6/xfrm6_state.c (ffffffff817fc9a9)
Location: include/net/xfrm.h:858
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (ffffffff8181cbb5)
Location: include/net/xfrm.h:854
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81821aa0)
Location: include/net/xfrm.h:854
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/ipv6/xfrm6_state.c (ffffffff8186c2c9)
Location: include/net/xfrm.h:854
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (ffffffff8184e485)
Location: include/net/xfrm.h:854
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/xfrm/xfrm_policy.c (ffffffff818532b0)
Location: include/net/xfrm.h:854
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/ipv6/xfrm6_state.c (ffffffff8189f0d9)
Location: include/net/xfrm.h:854
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (ffffffff81871ec5)
Location: include/net/xfrm.h:891
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81876c82)
Location: include/net/xfrm.h:891
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/ipv6/xfrm6_state.c (ffffffff818c565b)
Location: include/net/xfrm.h:891
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (ffffffff818f2885)
Location: include/net/xfrm.h:897
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f77d2)
Location: include/net/xfrm.h:897
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/ipv6/xfrm6_state.c (ffffffff8194893b)
Location: include/net/xfrm.h:897
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (ffffffff819491c1)
Location: include/net/xfrm.h:898
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194e1c4)
Location: include/net/xfrm.h:898
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/ipv6/xfrm6_state.c (ffffffff819a1a05)
Location: include/net/xfrm.h:898
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (ffffffff8197ae71)
Location: include/net/xfrm.h:916
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/xfrm/xfrm_policy.c (ffffffff819814c4)
Location: include/net/xfrm.h:916
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d8635)
Location: include/net/xfrm.h:916
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819eb292)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff819f36bc)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a22292)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2a58c)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1428c)
Location: include/net/xfrm.h:841
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17869)
Location: include/net/xfrm.h:841
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b2262c)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25939)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1022c)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13756)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd3b14)
Location: include/net/xfrm.h:840
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd789f)
Location: include/net/xfrm.h:840
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d6a1ec)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6e3db)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f35546)
Location: include/net/xfrm.h:860
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a032)
Location: include/net/xfrm.h:860
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f95063)
Location: include/net/xfrm.h:865
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81f99b0b)
Location: include/net/xfrm.h:865
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff82062453)
Location: include/net/xfrm.h:865
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff82066e6b)
Location: include/net/xfrm.h:865
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdf348)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3a30)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de888c)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (c0df0f40)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e01424)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (c000000000e0c4d8)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082e1e8)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffe000832bb0)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c1922)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff819c9c1c)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197e712)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81986a0c)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2c3a2)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3469c)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a37a72)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff81a400c0)
Location: include/net/xfrm.h:843
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
</ul>

## Differences
