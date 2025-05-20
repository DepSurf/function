# Function: <code>ip6mr_free_table</code>

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
In net/ipv6/ip6mr.c (ffffffff817f98e5)
Location: net/ipv6/ip6mr.c:334
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff81869156)
Location: net/ipv6/ip6mr.c:334
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff8189bfa6)
Location: net/ipv6/ip6mr.c:334
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff818c236b)
Location: net/ipv6/ip6mr.c:335
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff81945cab)
Location: net/ipv6/ip6mr.c:334
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199ec20)
Location: net/ipv6/ip6mr.c:383
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff8199ec20-ffffffff8199ec5e: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d55c0)
Location: net/ipv6/ip6mr.c:393
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff819d55c0-ffffffff819d55fe: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a444e0)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81a444e0-ffffffff81a44521: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a7b0d0)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81a7b0d0-ffffffff81a7b111: ip6mr_free_table (STB_LOCAL)
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
In net/ipv6/ip6mr.c (ffffffff81b757e3)
Location: net/ipv6/ip6mr.c:391
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff81b84553)
Location: net/ipv6/ip6mr.c:391
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff81b731f3)
Location: net/ipv6/ip6mr.c:391
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff81c3d7a3)
Location: net/ipv6/ip6mr.c:393
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff81ddc12b)
Location: net/ipv6/ip6mr.c:386
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff81faf34b)
Location: net/ipv6/ip6mr.c:393
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff8200f11b)
Location: net/ipv6/ip6mr.c:393
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv6/ip6mr.c (ffffffff820de0ab)
Location: net/ipv6/ip6mr.c:393
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d44fa8)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffff800010d44fa8-ffff800010d44ff8: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e47428)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
c0e47428-c0e47474: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e79a40)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
c000000000e79a40-c000000000e79ab0: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00087f886)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffe00087f886-ffffffe00087f8dc: ip6mr_free_table (STB_LOCAL)
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
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a1a760)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81a1a760-ffffffff81a1a7a1: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d7520)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff819d7520-ffffffff819d7561: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a851e0)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81a851e0-ffffffff81a85221: ip6mr_free_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6mr_free_table(struct mr_table *mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a91bc0)
Location: net/ipv6/ip6mr.c:387
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81a91bc0-ffffffff81a91c01: ip6mr_free_table (STB_LOCAL)
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
