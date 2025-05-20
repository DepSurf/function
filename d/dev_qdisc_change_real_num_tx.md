# Function: <code>dev_qdisc_change_real_num_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_qdisc_change_real_num_tx(struct net_device *dev, unsigned int new_real_tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0ff20)
Location: net/sched/sch_generic.c:1336
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
**Symbols:**

```
ffffffff81b0ff20-ffffffff81b0ff45: dev_qdisc_change_real_num_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_qdisc_change_real_num_tx(struct net_device *dev, unsigned int new_real_tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c970c0)
Location: net/sched/sch_generic.c:1378
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
**Symbols:**

```
ffffffff81c970c0-ffffffff81c970f9: dev_qdisc_change_real_num_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_qdisc_change_real_num_tx(struct net_device *dev, unsigned int new_real_tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e52ec0)
Location: net/sched/sch_generic.c:1390
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
**Symbols:**

```
ffffffff81e52ec0-ffffffff81e52ef9: dev_qdisc_change_real_num_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_qdisc_change_real_num_tx(struct net_device *dev, unsigned int new_real_tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eae740)
Location: net/sched/sch_generic.c:1398
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
**Symbols:**

```
ffffffff81eae740-ffffffff81eae779: dev_qdisc_change_real_num_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_qdisc_change_real_num_tx(struct net_device *dev, unsigned int new_real_tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f711d0)
Location: net/sched/sch_generic.c:1402
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
**Symbols:**

```
ffffffff81f711d0-ffffffff81f71209: dev_qdisc_change_real_num_tx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
