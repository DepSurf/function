# Function: <code>netdev_for_each_tx_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171bc00)
Location: include/linux/netdevice.h:1918
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff817419fe)
Location: include/linux/netdevice.h:1918
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817844a3)
Location: include/linux/netdevice.h:1958
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff817aedce)
Location: include/linux/netdevice.h:1958
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1aa7)
Location: include/linux/netdevice.h:1940
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff817de44e)
Location: include/linux/netdevice.h:1940
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cb808)
Location: include/linux/netdevice.h:1964
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff817fda9e)
Location: include/linux/netdevice.h:1964
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81845057)
Location: include/linux/netdevice.h:1980
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff8187b6be)
Location: include/linux/netdevice.h:1980
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818912b8)
Location: include/linux/netdevice.h:2048
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff818cdce5)
Location: include/linux/netdevice.h:2048
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b18e8)
Location: include/linux/netdevice.h:2113
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff818f8eb5)
Location: include/linux/netdevice.h:2113
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fe688)
Location: include/linux/netdevice.h:2102
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81958695)
Location: include/linux/netdevice.h:2102
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819309c5)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff8198eb45)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void netdev_for_each_tx_queue(struct net_device *dev, void (*f)(struct net_device *, struct netdev_queue *, void *), void *arg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a045f7)
Location: include/linux/netdevice.h:2200
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81a66925)
Location: include/linux/netdevice.h:2200
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81a669d5-ffffffff81a66a1f: netdev_for_each_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void netdev_for_each_tx_queue(struct net_device *dev, void (*f)(struct net_device *, struct netdev_queue *, void *), void *arg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06657)
Location: include/linux/netdevice.h:2264
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81a6ea05)
Location: include/linux/netdevice.h:2264
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81c31fe3-ffffffff81c3202d: netdev_for_each_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void netdev_for_each_tx_queue(struct net_device *dev, void (*f)(struct net_device *, struct netdev_queue *, void *), void *arg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed1a6)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81a57295)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81c242c6-ffffffff81c24310: netdev_for_each_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void netdev_for_each_tx_queue(struct net_device *dev, void (*f)(struct net_device *, struct netdev_queue *, void *), void *arg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9e3c2)
Location: include/linux/netdevice.h:2348
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81b100f5)
Location: include/linux/netdevice.h:2348
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81d38c7b-ffffffff81d38cc5: netdev_for_each_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void netdev_for_each_tx_queue(struct net_device *dev, void (*f)(struct net_device *, struct netdev_queue *, void *), void *arg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c12bf9)
Location: include/linux/netdevice.h:2428
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81c972b5)
Location: include/linux/netdevice.h:2428
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81f054df-ffffffff81f05534: netdev_for_each_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc2d1d)
Location: include/linux/netdevice.h:2455
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81e530e5)
Location: include/linux/netdevice.h:2455
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e321c5)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81eae965)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef0678)
Location: include/linux/netdevice.h:2567
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff81f71405)
Location: include/linux/netdevice.h:2567
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcc870)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffff800010c3a57c)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce6c6c)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (c0d4c72c)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cabbe0)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (c000000000d33674)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007582d6)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffe0007ab646)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d09c5)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff8192e9b5)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188a8a5)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff818e84b5)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819219c5)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff8197fb45)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81940395)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_generic.c (ffffffff819a20a5)
Location: include/linux/netdevice.h:2132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
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
</ul>
