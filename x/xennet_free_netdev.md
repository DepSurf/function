# Function: <code>xennet_free_netdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fa040)
Location: drivers/net/xen-netfront.c:1277
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff815fa040-ffffffff815fa070: xennet_free_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81659f00)
Location: drivers/net/xen-netfront.c:1268
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81659f00-ffffffff81659f30: xennet_free_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81687cb0)
Location: drivers/net/xen-netfront.c:1271
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81687cb0-ffffffff81687ce0: xennet_free_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169d070)
Location: drivers/net/xen-netfront.c:1270
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8169d070-ffffffff8169d0a0: xennet_free_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817080d0)
Location: drivers/net/xen-netfront.c:1272
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817080d0-ffffffff81708100: xennet_free_netdev (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff81749f8d)
Location: drivers/net/xen-netfront.c:1281
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
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
In drivers/net/xen-netfront.c (ffffffff8176e11d)
Location: drivers/net/xen-netfront.c:1280
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
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
In drivers/net/xen-netfront.c (ffffffff817ab10d)
Location: drivers/net/xen-netfront.c:1279
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
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
In drivers/net/xen-netfront.c (ffffffff817ceb4d)
Location: drivers/net/xen-netfront.c:1280
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
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
In drivers/net/xen-netfront.c (ffffffff81898e2a)
Location: drivers/net/xen-netfront.c:1282
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
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
In drivers/net/xen-netfront.c (ffffffff818a6e7a)
Location: drivers/net/xen-netfront.c:1511
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
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
In drivers/net/xen-netfront.c (ffffffff8188a61a)
Location: drivers/net/xen-netfront.c:1509
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
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
In drivers/net/xen-netfront.c (ffffffff8191d11a)
Location: drivers/net/xen-netfront.c:1660
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a73028)
Location: drivers/net/xen-netfront.c:1697
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81a70650-ffffffff81a70689: xennet_free_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c057d8)
Location: drivers/net/xen-netfront.c:1697
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81c03850-ffffffff81c03889: xennet_free_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c6aee8)
Location: drivers/net/xen-netfront.c:1697
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81c68ee0-ffffffff81c68f19: xennet_free_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xennet_free_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d1f8c8)
Location: drivers/net/xen-netfront.c:1698
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81d1d910-ffffffff81d1d949: xennet_free_netdev (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffff800010a078f0)
Location: drivers/net/xen-netfront.c:1280
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
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
In drivers/net/xen-netfront.c (ffffffff8179376d)
Location: drivers/net/xen-netfront.c:1312
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
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
In drivers/net/xen-netfront.c (ffffffff817c39cd)
Location: drivers/net/xen-netfront.c:1280
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
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
In drivers/net/xen-netfront.c (ffffffff817ddc8d)
Location: drivers/net/xen-netfront.c:1280
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
