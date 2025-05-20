# Function: <code>ip_del_fnhe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81754f90)
Location: net/ipv4/route.c:1560
Inline: True
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff81754f90-ffffffff817550e5: ip_del_fnhe.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817c1110)
Location: net/ipv4/route.c:1567
Inline: True
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff817c1110-ffffffff817c1265: ip_del_fnhe.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817f0710)
Location: net/ipv4/route.c:1577
Inline: True
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff817f0710-ffffffff817f0865: ip_del_fnhe.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81810b60)
Location: net/ipv4/route.c:1610
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81810b60-ffffffff81810cb7: ip_del_fnhe.isra.38 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff8188ffe0)
Location: net/ipv4/route.c:1623
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff8188ffe0-ffffffff8189013a: ip_del_fnhe.isra.37 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff818e2f40)
Location: net/ipv4/route.c:1289
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff8190fde0)
Location: net/ipv4/route.c:1288
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff81972376)
Location: net/ipv4/route.c:1325
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff819a8ce6)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff81a935b2)
Location: net/ipv4/route.c:1331
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9d462)
Location: net/ipv4/route.c:1337
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a881a7)
Location: net/ipv4/route.c:1325
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b42c47)
Location: net/ipv4/route.c:1321
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccf6a5)
Location: net/ipv4/route.c:1328
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8f8a5)
Location: net/ipv4/route.c:1328
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eedfa5)
Location: net/ipv4/route.c:1328
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb2105)
Location: net/ipv4/route.c:1330
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffff800010c599ac)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (c0d68224)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (c000000000d5a2b4)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffe0007c25a2)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff81948b56)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff81902646)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff819b3326)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
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
In net/ipv4/route.c (ffffffff819bc9f6)
Location: net/ipv4/route.c:1327
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
```
</details>
</li>
</ul>

## Differences
