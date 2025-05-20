# Function: <code>dev_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81741f20)
Location: net/sched/sch_generic.c:941
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81741f20-ffffffff81741fe2: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817aedc0)
Location: net/sched/sch_generic.c:968
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817aedc0-ffffffff817aee7b: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817de440)
Location: net/sched/sch_generic.c:976
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817de440-ffffffff817de4fb: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fda90)
Location: net/sched/sch_generic.c:976
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817fda90-ffffffff817fdb3c: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187b6b0)
Location: net/sched/sch_generic.c:1010
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8187b6b0-ffffffff8187b75c: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cdce0)
Location: net/sched/sch_generic.c:1277
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818cdce0-ffffffff818cdd8c: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f8eb0)
Location: net/sched/sch_generic.c:1314
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818f8eb0-ffffffff818f8f5c: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_generic.c (0)
Location: net/sched/sch_generic.c:1309
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81958773-ffffffff81958786: dev_shutdown.cold (STB_LOCAL)
ffffffff81958690-ffffffff81958740: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198eb40)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8198eb40-ffffffff8198ebf3: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a66920)
Location: net/sched/sch_generic.c:1330
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81a66920-ffffffff81a669d5: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6ea00)
Location: net/sched/sch_generic.c:1317
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81a6ea00-ffffffff81a6eab5: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a57290)
Location: net/sched/sch_generic.c:1363
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81a57290-ffffffff81a57345: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b100f0)
Location: net/sched/sch_generic.c:1402
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81b100f0-ffffffff81b101a5: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c972b0)
Location: net/sched/sch_generic.c:1468
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81c972b0-ffffffff81c97375: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e530e0)
Location: net/sched/sch_generic.c:1465
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81e530e0-ffffffff81e531a5: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eae960)
Location: net/sched/sch_generic.c:1473
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81eae960-ffffffff81eaea24: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f71400)
Location: net/sched/sch_generic.c:1477
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81f71400-ffffffff81f714c1: dev_shutdown (STB_GLOBAL)
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
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c3a560)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffff800010c3a560-ffff800010c3a620: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4c718)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c0d4c718-c0d4c7d8: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d33650)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c000000000d33650-c000000000d3373c: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007ab62c)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffe0007ab62c-ffffffe0007ab6ee: dev_shutdown (STB_GLOBAL)
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
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192e9b0)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8192e9b0-ffffffff8192ea63: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e84b0)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818e84b0-ffffffff818e8563: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197fb40)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8197fb40-ffffffff8197fbf3: dev_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_shutdown(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a20a0)
Location: net/sched/sch_generic.c:1306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff819a20a0-ffffffff819a2153: dev_shutdown (STB_GLOBAL)
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
