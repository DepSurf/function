# Function: <code>netlink_walk_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlink_walk_start(struct nl_seq_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174ac60)
Location: net/netlink/af_netlink.c:3077
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
**Symbols:**

```
ffffffff8174ac60-ffffffff8174acbe: netlink_walk_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlink_walk_start(struct nl_seq_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b7890)
Location: net/netlink/af_netlink.c:2345
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
**Symbols:**

```
ffffffff817b7890-ffffffff817b78fa: netlink_walk_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlink_walk_start(struct nl_seq_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e7330)
Location: net/netlink/af_netlink.c:2363
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
**Symbols:**

```
ffffffff817e7330-ffffffff817e7375: netlink_walk_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlink_walk_start(struct nl_seq_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81807030)
Location: net/netlink/af_netlink.c:2462
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
**Symbols:**

```
ffffffff81807030-ffffffff81807073: netlink_walk_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlink_walk_start(struct nl_seq_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81885de0)
Location: net/netlink/af_netlink.c:2479
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
**Symbols:**

```
ffffffff81885de0-ffffffff81885e23: netlink_walk_start (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff818d980b)
Location: net/netlink/af_netlink.c:2520
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81905ffb)
Location: net/netlink/af_netlink.c:2542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81967fd7)
Location: net/netlink/af_netlink.c:2542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff8199ea77)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81a76fb7)
Location: net/netlink/af_netlink.c:2534
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81a7fd47)
Location: net/netlink/af_netlink.c:2559
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81a68cc7)
Location: net/netlink/af_netlink.c:2569
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81b22287)
Location: net/netlink/af_netlink.c:2582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81caae66)
Location: net/netlink/af_netlink.c:2568
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81e67fc6)
Location: net/netlink/af_netlink.c:2641
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81ec3e36)
Location: net/netlink/af_netlink.c:2616
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff81f871f6)
Location: net/netlink/af_netlink.c:2610
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffff800010c4b470)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (c0d5c9fc)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (c000000000d4a4b8)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffe0007b94b0)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff8193e8e7)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff818f83e7)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff8198fa77)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
In net/netlink/af_netlink.c (ffffffff819b2357)
Location: net/netlink/af_netlink.c:2543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
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
</ul>
