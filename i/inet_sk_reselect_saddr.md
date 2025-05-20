# Function: <code>inet_sk_reselect_saddr</code>

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
In net/ipv4/af_inet.c (ffffffff81794562)
Location: net/ipv4/af_inet.c:1100
Inline: True
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
In net/ipv4/af_inet.c (ffffffff81801da4)
Location: net/ipv4/af_inet.c:1099
Inline: True
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
In net/ipv4/af_inet.c (ffffffff81832d34)
Location: net/ipv4/af_inet.c:1105
Inline: True
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
In net/ipv4/af_inet.c (ffffffff81854210)
Location: net/ipv4/af_inet.c:1123
Inline: True
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
In net/ipv4/af_inet.c (ffffffff818d4090)
Location: net/ipv4/af_inet.c:1127
Inline: True
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
In net/ipv4/af_inet.c (ffffffff8192a5a9)
Location: net/ipv4/af_inet.c:1182
Inline: True
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
In net/ipv4/af_inet.c (ffffffff81959d39)
Location: net/ipv4/af_inet.c:1182
Inline: True
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
In net/ipv4/af_inet.c (ffffffff819be698)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (ffffffff819f52c8)
Location: net/ipv4/af_inet.c:1188
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int inet_sk_reselect_saddr(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1220
Inline: False
```
**Symbols:**

```
ffffffff81ae3620-ffffffff81ae3845: inet_sk_reselect_saddr (STB_LOCAL)
ffffffff81ae47e2-ffffffff81ae4805: inet_sk_reselect_saddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inet_sk_reselect_saddr(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1218
Inline: False
```
**Symbols:**

```
ffffffff81af01a0-ffffffff81af03c5: inet_sk_reselect_saddr (STB_LOCAL)
ffffffff81c32910-ffffffff81c32933: inet_sk_reselect_saddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1222
Inline: True
```
**Symbols:**

```
ffffffff81adb850-ffffffff81adba75: inet_sk_reselect_saddr.constprop.0 (STB_LOCAL)
ffffffff81c24be4-ffffffff81c24c07: inet_sk_reselect_saddr.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1224
Inline: True
```
**Symbols:**

```
ffffffff81b9aa90-ffffffff81b9acb5: inet_sk_reselect_saddr.constprop.0 (STB_LOCAL)
ffffffff81d3c400-ffffffff81d3c423: inet_sk_reselect_saddr.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1219
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
**Symbols:**

```
ffffffff81d2c4d0-ffffffff81d2c6c9: inet_sk_reselect_saddr.constprop.0 (STB_LOCAL)
ffffffff81f08c1d-ffffffff81f08c40: inet_sk_reselect_saddr.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef4e00)
Location: net/ipv4/af_inet.c:1232
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
**Symbols:**

```
ffffffff81ef4e00-ffffffff81ef5054: inet_sk_reselect_saddr.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f546e0)
Location: net/ipv4/af_inet.c:1231
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
**Symbols:**

```
ffffffff81f546e0-ffffffff81f54934: inet_sk_reselect_saddr.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201a940)
Location: net/ipv4/af_inet.c:1251
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
**Symbols:**

```
ffffffff8201a940-ffffffff8201ab8e: inet_sk_reselect_saddr.constprop.0 (STB_LOCAL)
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
In net/ipv4/af_inet.c (ffff800010cab084)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (c0db7a3c)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (c000000000dc14e0)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (ffffffe000805b5e)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (ffffffff81995068)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (ffffffff8194eb28)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (ffffffff819ff908)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
In net/ipv4/af_inet.c (ffffffff81a09a12)
Location: net/ipv4/af_inet.c:1188
Inline: True
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
</ul>
