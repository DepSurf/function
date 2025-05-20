# Function: <code>tun_select_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, void *accel_priv, select_queue_fallback_t fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815ede80)
Location: drivers/net/tun.c:440
Inline: False
```
**Symbols:**

```
ffffffff815ede80-ffffffff815edf31: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, void *accel_priv, select_queue_fallback_t fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164ce40)
Location: drivers/net/tun.c:455
Inline: False
```
**Symbols:**

```
ffffffff8164ce40-ffffffff8164cf03: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, void *accel_priv, select_queue_fallback_t fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8167eb80)
Location: drivers/net/tun.c:455
Inline: False
```
**Symbols:**

```
ffffffff8167eb80-ffffffff8167ec43: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, void *accel_priv, select_queue_fallback_t fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81693d50)
Location: drivers/net/tun.c:457
Inline: False
```
**Symbols:**

```
ffffffff81693d50-ffffffff81693df5: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, void *accel_priv, select_queue_fallback_t fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816fdbb0)
Location: drivers/net/tun.c:540
Inline: False
```
**Symbols:**

```
ffffffff816fdbb0-ffffffff816fdc4e: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, void *accel_priv, select_queue_fallback_t fallback);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173c670)
Location: drivers/net/tun.c:609
Inline: True
```
**Symbols:**

```
ffffffff8173c670-ffffffff8173c775: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev, select_queue_fallback_t fallback);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817600c0)
Location: drivers/net/tun.c:608
Inline: True
```
**Symbols:**

```
ffffffff817600c0-ffffffff8176018c: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179dae0)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffffffff8179dae0-ffffffff8179dc12: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c17e0)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffffffff817c17e0-ffffffff817c1912: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188bad0)
Location: drivers/net/tun.c:571
Inline: False
```
**Symbols:**

```
ffffffff8188bad0-ffffffff8188bc17: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81899d60)
Location: drivers/net/tun.c:542
Inline: False
```
**Symbols:**

```
ffffffff81899d60-ffffffff81899e99: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187be20)
Location: drivers/net/tun.c:550
Inline: False
```
**Symbols:**

```
ffffffff8187be20-ffffffff8187bf57: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190d260)
Location: drivers/net/tun.c:556
Inline: False
```
**Symbols:**

```
ffffffff8190d260-ffffffff8190d39a: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a627a0)
Location: drivers/net/tun.c:561
Inline: False
```
**Symbols:**

```
ffffffff81a627a0-ffffffff81a628e9: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bee150)
Location: drivers/net/tun.c:561
Inline: False
```
**Symbols:**

```
ffffffff81bee150-ffffffff81bee299: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c46680)
Location: drivers/net/tun.c:561
Inline: False
```
**Symbols:**

```
ffffffff81c46680-ffffffff81c467c9: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfbf90)
Location: drivers/net/tun.c:561
Inline: False
```
**Symbols:**

```
ffffffff81cfbf90-ffffffff81cfc0d9: tun_select_queue (STB_LOCAL)
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
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109de1b0)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffff8000109de1b0-ffff8000109de318: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac6368)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
c0ac6368-c0ac6520: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa2d00)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
c000000000aa2d00-c000000000aa2ef8: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000626ba2)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffffffe000626ba2-ffffffe000626cfa: tun_select_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817862b0)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffffffff817862b0-ffffffff817863e2: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81765c00)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffffffff81765c00-ffffffff81765d32: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b6660)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffffffff817b6660-ffffffff817b6792: tun_select_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 tun_select_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d3ee0)
Location: drivers/net/tun.c:603
Inline: False
```
**Symbols:**

```
ffffffff817d3ee0-ffffffff817d4032: tun_select_queue (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *sb_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *accel_priv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>select_queue_fallback_t fallback</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
