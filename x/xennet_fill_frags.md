# Function: <code>xennet_fill_frags</code>

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
In drivers/net/xen-netfront.c (ffffffff815fb6f3)
Location: drivers/net/xen-netfront.c:872
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8165b619)
Location: drivers/net/xen-netfront.c:863
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81689439)
Location: drivers/net/xen-netfront.c:886
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8169eb64)
Location: drivers/net/xen-netfront.c:887
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81709d04)
Location: drivers/net/xen-netfront.c:889
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817487f3)
Location: drivers/net/xen-netfront.c:892
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8176c89d)
Location: drivers/net/xen-netfront.c:891
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817aa69d)
Location: drivers/net/xen-netfront.c:890
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817ce0fd)
Location: drivers/net/xen-netfront.c:890
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xennet_fill_frags(struct netfront_queue *queue, struct sk_buff *skb, struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818998c0)
Location: drivers/net/xen-netfront.c:892
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff818998c0-ffffffff81899a67: xennet_fill_frags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xennet_fill_frags(struct netfront_queue *queue, struct sk_buff *skb, struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a7df0)
Location: drivers/net/xen-netfront.c:1041
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff818a7df0-ffffffff818a7f97: xennet_fill_frags (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff8188c3e9)
Location: drivers/net/xen-netfront.c:1039
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8191f7d2)
Location: drivers/net/xen-netfront.c:1118
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81a748ae)
Location: drivers/net/xen-netfront.c:1157
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81c08b0e)
Location: drivers/net/xen-netfront.c:1157
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81c6e275)
Location: drivers/net/xen-netfront.c:1157
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81d22b5d)
Location: drivers/net/xen-netfront.c:1158
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffff800010a088e4)
Location: drivers/net/xen-netfront.c:890
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81792d1d)
Location: drivers/net/xen-netfront.c:922
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c2f7d)
Location: drivers/net/xen-netfront.c:890
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817dd23d)
Location: drivers/net/xen-netfront.c:890
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
