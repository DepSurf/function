# Function: <code>setup_netfront</code>

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
In drivers/net/xen-netfront.c (ffffffff815fc8ae)
Location: drivers/net/xen-netfront.c:1529
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
In drivers/net/xen-netfront.c (ffffffff8165c7fe)
Location: drivers/net/xen-netfront.c:1520
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
In drivers/net/xen-netfront.c (ffffffff8168a62e)
Location: drivers/net/xen-netfront.c:1527
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
In drivers/net/xen-netfront.c (ffffffff8169f8e7)
Location: drivers/net/xen-netfront.c:1526
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
In drivers/net/xen-netfront.c (ffffffff8170aa7b)
Location: drivers/net/xen-netfront.c:1529
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
In drivers/net/xen-netfront.c (ffffffff817495f0)
Location: drivers/net/xen-netfront.c:1533
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
In drivers/net/xen-netfront.c (ffffffff8176d6a1)
Location: drivers/net/xen-netfront.c:1532
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
In drivers/net/xen-netfront.c (ffffffff817ab90b)
Location: drivers/net/xen-netfront.c:1531
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
In drivers/net/xen-netfront.c (ffffffff817cf34b)
Location: drivers/net/xen-netfront.c:1532
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
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81897500)
Location: drivers/net/xen-netfront.c:1537
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81897500-ffffffff818977a1: setup_netfront (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a5a00)
Location: drivers/net/xen-netfront.c:1769
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff818a5a00-ffffffff818a5ca1: setup_netfront (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81888c60)
Location: drivers/net/xen-netfront.c:1767
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81888c60-ffffffff8188905c: setup_netfront (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8191b470)
Location: drivers/net/xen-netfront.c:1923
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8191b470-ffffffff8191b866: setup_netfront (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a713a0)
Location: drivers/net/xen-netfront.c:1960
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a713a0-ffffffff81a71752: setup_netfront (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c03f30)
Location: drivers/net/xen-netfront.c:1966
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81c03f30-ffffffff81c042e2: setup_netfront (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c69630)
Location: drivers/net/xen-netfront.c:1968
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81c69630-ffffffff81c699e8: setup_netfront (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int setup_netfront(struct xenbus_device *dev, struct netfront_queue *queue, unsigned int feature_split_evtchn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d1dfe0)
Location: drivers/net/xen-netfront.c:1969
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81d1dfe0-ffffffff81d1e39f: setup_netfront (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffff800010a07fd4)
Location: drivers/net/xen-netfront.c:1532
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
In drivers/net/xen-netfront.c (ffffffff81793f6b)
Location: drivers/net/xen-netfront.c:1566
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
In drivers/net/xen-netfront.c (ffffffff817c41cb)
Location: drivers/net/xen-netfront.c:1532
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
In drivers/net/xen-netfront.c (ffffffff817de47b)
Location: drivers/net/xen-netfront.c:1532
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
