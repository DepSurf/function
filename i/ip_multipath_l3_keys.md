# Function: <code>ip_multipath_l3_keys</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8180fb98)
Location: net/ipv4/route.c:1755
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
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
In net/ipv4/route.c (ffffffff8188f0c8)
Location: net/ipv4/route.c:1768
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
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
In net/ipv4/route.c (ffffffff818e480c)
Location: net/ipv4/route.c:1786
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
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
In net/ipv4/route.c (ffffffff81911736)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81971e70)
Location: net/ipv4/route.c:1874
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81971e70-ffffffff81971f9a: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff819a8870)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff819a8870-ffffffff819a899a: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81a91ff0)
Location: net/ipv4/route.c:1880
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81a91ff0-ffffffff81a92112: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9be90)
Location: net/ipv4/route.c:1886
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81a9be90-ffffffff81a9bfb2: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81a86e40)
Location: net/ipv4/route.c:1874
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81a86e40-ffffffff81a86f6d: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81b41600)
Location: net/ipv4/route.c:1870
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81b41600-ffffffff81b4172d: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81cce030)
Location: net/ipv4/route.c:1892
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81cce030-ffffffff81cce199: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81e8dff0)
Location: net/ipv4/route.c:1887
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81e8dff0-ffffffff81e8e159: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81eec730)
Location: net/ipv4/route.c:1885
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81eec730-ffffffff81eec898: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81fb0790)
Location: net/ipv4/route.c:1887
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff81fb0790-ffffffff81fb08f8: ip_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffff800010c58180)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffff800010c58180-ffff800010c582e0: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *hash_keys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d67eac)
Location: net/ipv4/route.c:1878
Inline: False
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
c0d67eac-c0d6800c: ip_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (c000000000d59b30)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
c000000000d59b30-c000000000d59d28: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c2396)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffe0007c2396-ffffffe0007c24a4: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff819486e0)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff819486e0-ffffffff8194880a: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff819021d0)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff819021d0-ffffffff819022fa: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff819b2eb0)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff819b2eb0-ffffffff819b2fda: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff819bc580)
Location: net/ipv4/route.c:1878
Inline: True
Direct callers:
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff819bc580-ffffffff819bc6aa: ip_multipath_l3_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
