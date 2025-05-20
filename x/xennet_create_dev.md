# Function: <code>xennet_create_dev</code>

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
In drivers/net/xen-netfront.c (ffffffff815fa583)
Location: drivers/net/xen-netfront.c:1286
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff8165a446)
Location: drivers/net/xen-netfront.c:1277
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff81688196)
Location: drivers/net/xen-netfront.c:1280
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff8169d536)
Location: drivers/net/xen-netfront.c:1279
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff81708426)
Location: drivers/net/xen-netfront.c:1281
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff81747121)
Location: drivers/net/xen-netfront.c:1290
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff8176b231)
Location: drivers/net/xen-netfront.c:1289
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff817a9020)
Location: drivers/net/xen-netfront.c:1288
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff817cca90)
Location: drivers/net/xen-netfront.c:1289
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818979a0)
Location: drivers/net/xen-netfront.c:1291
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff818979a0-ffffffff81897c11: xennet_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a5d60)
Location: drivers/net/xen-netfront.c:1520
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff818a5d60-ffffffff818a5fd9: xennet_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81889110)
Location: drivers/net/xen-netfront.c:1518
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81889110-ffffffff81889395: xennet_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8191bc70)
Location: drivers/net/xen-netfront.c:1669
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8191bc70-ffffffff8191bf49: xennet_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a70dd0)
Location: drivers/net/xen-netfront.c:1706
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81a70dd0-ffffffff81a710b7: xennet_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c04c30)
Location: drivers/net/xen-netfront.c:1706
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81c04c30-ffffffff81c04f35: xennet_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c6a340)
Location: drivers/net/xen-netfront.c:1706
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81c6a340-ffffffff81c6a650: xennet_create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *xennet_create_dev(struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d1ed20)
Location: drivers/net/xen-netfront.c:1707
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81d1ed20-ffffffff81d1f02d: xennet_create_dev (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffff800010a064fc)
Location: drivers/net/xen-netfront.c:1289
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff81791770)
Location: drivers/net/xen-netfront.c:1321
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff817c1910)
Location: drivers/net/xen-netfront.c:1289
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff817dbbd0)
Location: drivers/net/xen-netfront.c:1289
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
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
