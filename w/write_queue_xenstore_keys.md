# Function: <code>write_queue_xenstore_keys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fbf00)
Location: drivers/net/xen-netfront.c:1655
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815fbf00-ffffffff815fc13e: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165be60)
Location: drivers/net/xen-netfront.c:1646
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8165be60-ffffffff8165c09e: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81689c80)
Location: drivers/net/xen-netfront.c:1653
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81689c80-ffffffff81689ebe: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169f3d0)
Location: drivers/net/xen-netfront.c:1652
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8169f3d0-ffffffff8169f611: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8170a570)
Location: drivers/net/xen-netfront.c:1654
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8170a570-ffffffff8170a7b1: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81749050)
Location: drivers/net/xen-netfront.c:1660
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81749050-ffffffff81749285: write_queue_xenstore_keys.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8176d2e0)
Location: drivers/net/xen-netfront.c:1659
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8176d2e0-ffffffff8176d518: write_queue_xenstore_keys.isra.33 (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff817ab530)
Location: drivers/net/xen-netfront.c:1658
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817ab530-ffffffff817ab76a: write_queue_xenstore_keys.isra.0 (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff817cef70)
Location: drivers/net/xen-netfront.c:1659
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817cef70-ffffffff817cf1aa: write_queue_xenstore_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818982a0)
Location: drivers/net/xen-netfront.c:1664
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff818982a0-ffffffff818984d7: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a6660)
Location: drivers/net/xen-netfront.c:1896
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff818a6660-ffffffff818a6897: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81889a80)
Location: drivers/net/xen-netfront.c:1894
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81889a80-ffffffff81889cb7: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8191c590)
Location: drivers/net/xen-netfront.c:2059
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8191c590-ffffffff8191c7c7: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a71b40)
Location: drivers/net/xen-netfront.c:2067
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a71b40-ffffffff81a71d8a: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c04300)
Location: drivers/net/xen-netfront.c:2073
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81c04300-ffffffff81c0454a: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c69a00)
Location: drivers/net/xen-netfront.c:2075
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81c69a00-ffffffff81c69c4a: write_queue_xenstore_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int write_queue_xenstore_keys(struct netfront_queue *queue, struct xenbus_transaction *xbt, int write_hierarchical);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d1e3b0)
Location: drivers/net/xen-netfront.c:2076
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81d1e3b0-ffffffff81d1e5fa: write_queue_xenstore_keys (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffff800010a06f98)
Location: drivers/net/xen-netfront.c:1659
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff800010a06f98-ffff800010a071dc: write_queue_xenstore_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/net/xen-netfront.c (ffffffff81793b90)
Location: drivers/net/xen-netfront.c:1693
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81793b90-ffffffff81793dca: write_queue_xenstore_keys.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c3df0)
Location: drivers/net/xen-netfront.c:1659
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817c3df0-ffffffff817c402a: write_queue_xenstore_keys.isra.0 (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff817de0a0)
Location: drivers/net/xen-netfront.c:1659
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817de0a0-ffffffff817de2da: write_queue_xenstore_keys.isra.0 (STB_LOCAL)
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
