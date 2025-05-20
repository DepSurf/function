# Function: <code>__netlink_lookup</code>

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
In net/netlink/af_netlink.c (ffffffff8174bdf9)
Location: net/netlink/af_netlink.c:1046
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
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
In net/netlink/af_netlink.c (ffffffff817b8cb9)
Location: net/netlink/af_netlink.c:432
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e8750)
Location: net/netlink/af_netlink.c:439
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff817e8750-ffffffff817e8870: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81808710)
Location: net/netlink/af_netlink.c:470
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff81808710-ffffffff81808846: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81887590)
Location: net/netlink/af_netlink.c:472
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff81887590-ffffffff818876c6: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818dac60)
Location: net/netlink/af_netlink.c:506
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff818dac60-ffffffff818dad96: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81907540)
Location: net/netlink/af_netlink.c:506
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff81907540-ffffffff81907696: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819687f0)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff819687f0-ffffffff81968942: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199f290)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff8199f290-ffffffff8199f3e2: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a78680)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a78680-ffffffff81a787a2: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a819a0)
Location: net/netlink/af_netlink.c:498
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a819a0-ffffffff81a81aa7: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6aaa0)
Location: net/netlink/af_netlink.c:508
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a6aaa0-ffffffff81a6ab94: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b240a0)
Location: net/netlink/af_netlink.c:508
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81b240a0-ffffffff81b24194: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cac6e0)
Location: net/netlink/af_netlink.c:512
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81cad870-ffffffff81cad9cc: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6a2e0)
Location: net/netlink/af_netlink.c:512
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81e6ae40-ffffffff81e6af9c: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec62a0)
Location: net/netlink/af_netlink.c:512
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81ec6950-ffffffff81ec6abe: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f89510)
Location: net/netlink/af_netlink.c:510
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81f89bc0-ffffffff81f89d2e: __netlink_lookup (STB_LOCAL)
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
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4cda8)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffff800010c4cda8-ffff800010c4cf44: __netlink_lookup (STB_LOCAL)
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
In net/netlink/af_netlink.c (c0d5df74)
Location: net/netlink/af_netlink.c:497
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4bb80)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
c000000000d4bb80-c000000000d4bd5c: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b9ca6)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_autobind
```
**Symbols:**

```
ffffffe0007b9ca6-ffffffe0007b9e1c: __netlink_lookup (STB_LOCAL)
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
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193f100)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff8193f100-ffffffff8193f252: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f8c00)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff818f8c00-ffffffff818f8d52: __netlink_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__netlink_lookup(struct netlink_table *table, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81990290)
Location: net/netlink/af_netlink.c:497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff81990290-ffffffff819903e2: __netlink_lookup (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff819b2baa)
Location: net/netlink/af_netlink.c:497
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
