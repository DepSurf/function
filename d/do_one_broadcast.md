# Function: <code>do_one_broadcast</code>

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
In net/netlink/af_netlink.c (ffffffff8174b989)
Location: net/netlink/af_netlink.c:1999
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff817b896d)
Location: net/netlink/af_netlink.c:1306
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff817e841d)
Location: net/netlink/af_netlink.c:1323
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff818083ee)
Location: net/netlink/af_netlink.c:1357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff8188724e)
Location: net/netlink/af_netlink.c:1370
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff818da90d)
Location: net/netlink/af_netlink.c:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff819071ed)
Location: net/netlink/af_netlink.c:1402
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff819684a8)
Location: net/netlink/af_netlink.c:1402
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff8199ef48)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a78c70)
Location: net/netlink/af_netlink.c:1403
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
**Symbols:**

```
ffffffff81a78c70-ffffffff81a78f93: do_one_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a814a0)
Location: net/netlink/af_netlink.c:1404
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
**Symbols:**

```
ffffffff81a814a0-ffffffff81a817c3: do_one_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6a5d0)
Location: net/netlink/af_netlink.c:1414
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
**Symbols:**

```
ffffffff81a6a5d0-ffffffff81a6a8d0: do_one_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b23bd0)
Location: net/netlink/af_netlink.c:1419
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
**Symbols:**

```
ffffffff81b23bd0-ffffffff81b23ed0: do_one_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cad3d0)
Location: net/netlink/af_netlink.c:1417
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast
```
**Symbols:**

```
ffffffff81cad3d0-ffffffff81cad6cc: do_one_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6a980)
Location: net/netlink/af_netlink.c:1437
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast
```
**Symbols:**

```
ffffffff81e6a980-ffffffff81e6ac7c: do_one_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec6df0)
Location: net/netlink/af_netlink.c:1437
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast
```
**Symbols:**

```
ffffffff81ec6df0-ffffffff81ec70ec: do_one_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_one_broadcast(struct sock *sk, struct netlink_broadcast_data *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8a070)
Location: net/netlink/af_netlink.c:1439
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
**Symbols:**

```
ffffffff81f8a070-ffffffff81f8a396: do_one_broadcast (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffff800010c4c218)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (c0d5cf9c)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (c000000000d4abe0)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffe0007b95a6)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff8193edb8)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff818f88b8)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff8198ff48)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
In net/netlink/af_netlink.c (ffffffff819b2817)
Location: net/netlink/af_netlink.c:1403
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
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
