# Function: <code>xennet_create_queues</code>

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
In drivers/net/xen-netfront.c (ffffffff815fc6f6)
Location: drivers/net/xen-netfront.c:1758
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
In drivers/net/xen-netfront.c (ffffffff8165c651)
Location: drivers/net/xen-netfront.c:1749
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
In drivers/net/xen-netfront.c (ffffffff8168a46e)
Location: drivers/net/xen-netfront.c:1755
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
In drivers/net/xen-netfront.c (ffffffff8169f73b)
Location: drivers/net/xen-netfront.c:1754
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
In drivers/net/xen-netfront.c (ffffffff8170a8e4)
Location: drivers/net/xen-netfront.c:1756
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
In drivers/net/xen-netfront.c (ffffffff817493bc)
Location: drivers/net/xen-netfront.c:1758
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1757
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8176d0f0-ffffffff8176d2dc: xennet_create_queues (STB_LOCAL)
ffffffff8176e5a6-ffffffff8176e5ed: xennet_create_queues.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1756
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817aaeb0-ffffffff817ab080: xennet_create_queues (STB_LOCAL)
ffffffff817ac39a-ffffffff817ac3ff: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1757
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817ce8f0-ffffffff817ceac0: xennet_create_queues (STB_LOCAL)
ffffffff817cfdda-ffffffff817cfe3f: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1762
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81898570-ffffffff81898664: xennet_create_queues (STB_LOCAL)
ffffffff8189a738-ffffffff8189a77b: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2039
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff818a6930-ffffffff818a6a44: xennet_create_queues (STB_LOCAL)
ffffffff81c19d40-ffffffff81c19da7: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2037
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81889cc0-ffffffff81889fc3: xennet_create_queues (STB_LOCAL)
ffffffff81c0bb04-ffffffff81c0bbe7: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2186
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8191c7d0-ffffffff8191cb81: xennet_create_queues.constprop.0 (STB_LOCAL)
ffffffff81d11220-ffffffff81d11303: xennet_create_queues.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:2194
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a71d90-ffffffff81a7213f: xennet_create_queues.constprop.0 (STB_LOCAL)
ffffffff81edbef8-ffffffff81edbfd9: xennet_create_queues.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c04560)
Location: drivers/net/xen-netfront.c:2200
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81c04560-ffffffff81c049db: xennet_create_queues.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c69c60)
Location: drivers/net/xen-netfront.c:2202
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81c69c60-ffffffff81c6a0ee: xennet_create_queues.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d1e610)
Location: drivers/net/xen-netfront.c:2203
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81d1e610-ffffffff81d1eacb: xennet_create_queues.constprop.0 (STB_LOCAL)
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
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a07aa0)
Location: drivers/net/xen-netfront.c:1757
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff800010a07aa0-ffff800010a07d38: xennet_create_queues (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1791
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81793510-ffffffff817936e0: xennet_create_queues (STB_LOCAL)
ffffffff81794a4e-ffffffff81794ab3: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1757
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817c3770-ffffffff817c3940: xennet_create_queues (STB_LOCAL)
ffffffff817c4c5a-ffffffff817c4cbf: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xennet_create_queues(struct netfront_info *info, unsigned int *num_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1757
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817dda30-ffffffff817ddc00: xennet_create_queues (STB_LOCAL)
ffffffff817def01-ffffffff817def66: xennet_create_queues.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
