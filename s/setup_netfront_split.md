# Function: <code>setup_netfront_split</code>

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
In drivers/net/xen-netfront.c (ffffffff815fca2d)
Location: drivers/net/xen-netfront.c:1485
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8165c97f)
Location: drivers/net/xen-netfront.c:1476
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8168a7a9)
Location: drivers/net/xen-netfront.c:1483
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
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
In drivers/net/xen-netfront.c (ffffffff8169fd4a)
Location: drivers/net/xen-netfront.c:1482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8170aed8)
Location: drivers/net/xen-netfront.c:1485
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff817499d5)
Location: drivers/net/xen-netfront.c:1489
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8176da24)
Location: drivers/net/xen-netfront.c:1488
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff817abc2e)
Location: drivers/net/xen-netfront.c:1487
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff817cf66e)
Location: drivers/net/xen-netfront.c:1488
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int setup_netfront_split(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818973b0)
Location: drivers/net/xen-netfront.c:1493
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff818973b0-ffffffff818974f6: setup_netfront_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setup_netfront_split(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a58b0)
Location: drivers/net/xen-netfront.c:1725
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff818a58b0-ffffffff818a59f6: setup_netfront_split (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff81888ef7)
Location: drivers/net/xen-netfront.c:1723
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:setup_netfront
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
In drivers/net/xen-netfront.c (ffffffff8191b6fc)
Location: drivers/net/xen-netfront.c:1879
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:setup_netfront
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
In drivers/net/xen-netfront.c (ffffffff81a7160a)
Location: drivers/net/xen-netfront.c:1916
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:setup_netfront
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
In drivers/net/xen-netfront.c (ffffffff81c0419a)
Location: drivers/net/xen-netfront.c:1922
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:setup_netfront
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
In drivers/net/xen-netfront.c (ffffffff81c69897)
Location: drivers/net/xen-netfront.c:1924
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:setup_netfront
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
In drivers/net/xen-netfront.c (ffffffff81d1e24e)
Location: drivers/net/xen-netfront.c:1925
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:setup_netfront
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
In drivers/net/xen-netfront.c (ffff800010a08104)
Location: drivers/net/xen-netfront.c:1488
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8179428e)
Location: drivers/net/xen-netfront.c:1522
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff817c44ee)
Location: drivers/net/xen-netfront.c:1488
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff817de79e)
Location: drivers/net/xen-netfront.c:1488
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
