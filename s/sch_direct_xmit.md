# Function: <code>sch_direct_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817413e0)
Location: net/sched/sch_generic.c:149
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff817413e0-ffffffff817415e8: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ae1f0)
Location: net/sched/sch_generic.c:166
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff817ae1f0-ffffffff817ae3a2: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817dd880)
Location: net/sched/sch_generic.c:166
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff817dd880-ffffffff817dda32: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fceb0)
Location: net/sched/sch_generic.c:166
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff817fceb0-ffffffff817fd05c: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187a840)
Location: net/sched/sch_generic.c:171
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff8187a840-ffffffff8187a9f8: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:299
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff818cdd8c-ffffffff818cddab: sch_direct_xmit.cold.57 (STB_LOCAL)
ffffffff818cc820-ffffffff818ccb89: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:299
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff818f8f5c-ffffffff818f8f7b: sch_direct_xmit.cold.57 (STB_LOCAL)
ffffffff818f7b70-ffffffff818f7eff: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81958740-ffffffff8195875f: sch_direct_xmit.cold (STB_LOCAL)
ffffffff819572f0-ffffffff81957629: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff8198ebf3-ffffffff8198ec12: sch_direct_xmit.cold (STB_LOCAL)
ffffffff8198d790-ffffffff8198dac9: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81a66a1f-ffffffff81a66a3e: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81a659b0-ffffffff81a65ce9: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81c3202d-ffffffff81c3204c: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81a6dad0-ffffffff81a6de09: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:308
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81c24310-ffffffff81c2432f: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81a56310-ffffffff81a56672: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:314
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81d38cd9-ffffffff81d38d14: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81b0f0d0-ffffffff81b0f456: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:314
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81f05549-ffffffff81f05581: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81c962d0-ffffffff81c965f9: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:314
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff820ad57d-ffffffff820ad598: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81e51ec0-ffffffff81e52201: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:314
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff8212e727-ffffffff8212e742: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81ead730-ffffffff81eada71: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:314
Inline: False
Direct callers:
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff822104c5-ffffffff822104e0: sch_direct_xmit.cold (STB_LOCAL)
ffffffff81f701d0-ffffffff81f70515: sch_direct_xmit (STB_GLOBAL)
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
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c38c68)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffff800010c38c68-ffff800010c391b0: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4b098)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
c0d4b098-c0d4b4ec: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d317b0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
c000000000d317b0-c000000000d31d1c: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007aa21a)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffe0007aa21a-ffffffe0007aa618: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff8192ea63-ffffffff8192ea82: sch_direct_xmit.cold (STB_LOCAL)
ffffffff8192d600-ffffffff8192d939: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff818e8563-ffffffff818e8582: sch_direct_xmit.cold (STB_LOCAL)
ffffffff818e7100-ffffffff818e7439: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff8197fbf3-ffffffff8197fc12: sch_direct_xmit.cold (STB_LOCAL)
ffffffff8197e790-ffffffff8197eac9: sch_direct_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool sch_direct_xmit(struct sk_buff *skb, struct Qdisc *q, struct net_device *dev, struct netdev_queue *txq, spinlock_t *root_lock, bool validate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:285
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff819a2153-ffffffff819a2172: sch_direct_xmit.cold (STB_LOCAL)
ffffffff819a0d00-ffffffff819a103f: sch_direct_xmit (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
