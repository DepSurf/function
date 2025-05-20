# Function: <code>xennet_get_extras</code>

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
In drivers/net/xen-netfront.c (ffffffff815fba7e)
Location: drivers/net/xen-netfront.c:719
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
In drivers/net/xen-netfront.c (ffffffff8165b89b)
Location: drivers/net/xen-netfront.c:710
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
In drivers/net/xen-netfront.c (ffffffff81689673)
Location: drivers/net/xen-netfront.c:733
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
In drivers/net/xen-netfront.c (ffffffff8169ee70)
Location: drivers/net/xen-netfront.c:734
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
In drivers/net/xen-netfront.c (ffffffff8170a007)
Location: drivers/net/xen-netfront.c:736
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
In drivers/net/xen-netfront.c (ffffffff81748aea)
Location: drivers/net/xen-netfront.c:739
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
In drivers/net/xen-netfront.c (ffffffff8176cb8e)
Location: drivers/net/xen-netfront.c:738
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
In drivers/net/xen-netfront.c (ffffffff817aa86b)
Location: drivers/net/xen-netfront.c:737
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
In drivers/net/xen-netfront.c (ffffffff817ce298)
Location: drivers/net/xen-netfront.c:737
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xennet_get_extras(struct netfront_queue *queue, struct xen_netif_extra_info *extras, RING_IDX rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:739
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
```
**Symbols:**

```
ffffffff81899a70-ffffffff81899bda: xennet_get_extras (STB_LOCAL)
ffffffff8189a791-ffffffff8189a7d1: xennet_get_extras.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xennet_get_extras(struct netfront_queue *queue, struct xen_netif_extra_info *extras, RING_IDX rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:814
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
```
**Symbols:**

```
ffffffff818a7fa0-ffffffff818a810a: xennet_get_extras (STB_LOCAL)
ffffffff81c19dce-ffffffff81c19e0e: xennet_get_extras.cold (STB_LOCAL)
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
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:812
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
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
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:888
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
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
In drivers/net/xen-netfront.c (ffffffff81a7437c)
Location: drivers/net/xen-netfront.c:925
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
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
In drivers/net/xen-netfront.c (ffffffff81c084fa)
Location: drivers/net/xen-netfront.c:925
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
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
In drivers/net/xen-netfront.c (ffffffff81c6dc14)
Location: drivers/net/xen-netfront.c:925
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
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
In drivers/net/xen-netfront.c (ffffffff81d22559)
Location: drivers/net/xen-netfront.c:926
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_get_responses
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
In drivers/net/xen-netfront.c (ffff800010a08bc4)
Location: drivers/net/xen-netfront.c:737
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
In drivers/net/xen-netfront.c (ffffffff81792eb8)
Location: drivers/net/xen-netfront.c:769
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
In drivers/net/xen-netfront.c (ffffffff817c3118)
Location: drivers/net/xen-netfront.c:737
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
In drivers/net/xen-netfront.c (ffffffff817dd3d8)
Location: drivers/net/xen-netfront.c:737
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
