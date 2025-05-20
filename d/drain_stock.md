# Function: <code>drain_stock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff811fb500)
Location: mm/memcontrol.c:1906
Inline: True
Direct callers:
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:memcg_cpu_hotplug_callback
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff811fb500-ffffffff811fb59a: drain_stock.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8121f080)
Location: mm/memcontrol.c:1765
Inline: True
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_cpu_hotplug_callback
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff8121f080-ffffffff8121f11d: drain_stock.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81231590)
Location: mm/memcontrol.c:1736
Inline: True
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff81231590-ffffffff8123162d: drain_stock.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8123cdc0)
Location: mm/memcontrol.c:1747
Inline: True
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff8123cdc0-ffffffff8123ce5e: drain_stock.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8125c8d0)
Location: mm/memcontrol.c:1761
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff8125c8d0-ffffffff8125c973: drain_stock.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81280560)
Location: mm/memcontrol.c:1713
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff81280560-ffffffff81280603: drain_stock.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81295110)
Location: mm/memcontrol.c:1991
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff81295110-ffffffff812951b3: drain_stock.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812b10d0)
Location: mm/memcontrol.c:2192
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff812b10d0-ffffffff812b1173: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812c2b30)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff812c2b30-ffffffff812c2bd3: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f8680)
Location: mm/memcontrol.c:2085
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff812f8680-ffffffff812f8724: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81304170)
Location: mm/memcontrol.c:2302
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff81304170-ffffffff81304213: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130a360)
Location: mm/memcontrol.c:2111
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff8130a360-ffffffff8130a403: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81352faa)
Location: mm/memcontrol.c:2207
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
Direct callers:
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff81352ee0-ffffffff81352f7e: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cd9fa)
Location: mm/memcontrol.c:2192
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
Direct callers:
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff813cd840-ffffffff813cd8ed: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814525da)
Location: mm/memcontrol.c:2252
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
Direct callers:
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff814523e0-ffffffff8145248d: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814880ea)
Location: mm/memcontrol.c:2262
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
Direct callers:
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff81487ef0-ffffffff81487f9d: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b7f1a)
Location: mm/memcontrol.c:2334
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
Direct callers:
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff814b7b60-ffffffff814b7c0d: drain_stock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffff800010365158)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffff800010365158-ffff800010365200: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drain_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0556f08)
Location: mm/memcontrol.c:2208
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
c0556f08-c0556ffc: drain_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c000000000451e50)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
c000000000451e50-c000000000451fac: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffe000243bfe)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffe000243bfe-ffffffe000243ce2: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb110)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff812bb110-ffffffff812bb1b3: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812ac290)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff812ac290-ffffffff812ac333: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812b8f20)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff812b8f20-ffffffff812b8fc3: drain_stock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812c9550)
Location: mm/memcontrol.c:2208
Inline: True
Direct callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff812c9550-ffffffff812c9608: drain_stock.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
