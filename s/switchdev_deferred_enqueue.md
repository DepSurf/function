# Function: <code>switchdev_deferred_enqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8188a780)
Location: net/switchdev/switchdev.c:158
Inline: False
```
**Symbols:**

```
ffffffff8188a780-ffffffff8188a835: switchdev_deferred_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818beb30)
Location: net/switchdev/switchdev.c:157
Inline: False
```
**Symbols:**

```
ffffffff818beb30-ffffffff818bebe5: switchdev_deferred_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818e5630)
Location: net/switchdev/switchdev.c:157
Inline: False
```
**Symbols:**

```
ffffffff818e5630-ffffffff818e56ff: switchdev_deferred_enqueue (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffffffff8196b759)
Location: net/switchdev/switchdev.c:157
Inline: True
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
In net/switchdev/switchdev.c (ffffffff819c51b9)
Location: net/switchdev/switchdev.c:157
Inline: True
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
In net/switchdev/switchdev.c (ffffffff819fc809)
Location: net/switchdev/switchdev.c:157
Inline: True
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
In net/switchdev/switchdev.c (ffffffff81a6bb60)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff81a6bb60-ffffffff81a6bc37: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffffffff81aa2540)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff81aa2540-ffffffff81aa2617: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9df20)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff81b9df20-ffffffff81b9dff7: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad840)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff81bad840-ffffffff81bad917: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c990)
Location: net/switchdev/switchdev.c:81
Inline: False
```
**Symbols:**

```
ffffffff81b9c990-ffffffff81b9ca5f: switchdev_deferred_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c69b80)
Location: net/switchdev/switchdev.c:81
Inline: False
```
**Symbols:**

```
ffffffff81c69b80-ffffffff81c69c54: switchdev_deferred_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0ccb0)
Location: net/switchdev/switchdev.c:82
Inline: False
```
**Symbols:**

```
ffffffff81e0ccb0-ffffffff81e0cd94: switchdev_deferred_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe2ea0)
Location: net/switchdev/switchdev.c:82
Inline: False
```
**Symbols:**

```
ffffffff81fe2ea0-ffffffff81fe2f84: switchdev_deferred_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205f1c0)
Location: net/switchdev/switchdev.c:82
Inline: False
```
**Symbols:**

```
ffffffff8205f1c0-ffffffff8205f2a4: switchdev_deferred_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82132110)
Location: net/switchdev/switchdev.c:111
Inline: False
```
**Symbols:**

```
ffffffff82132110-ffffffff821321f4: switchdev_deferred_enqueue (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffff800010d73ca0)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffff800010d73ca0-ffff800010d73df4: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int switchdev_deferred_enqueue(struct net_device *dev, const void *data, size_t data_len, switchdev_deferred_func_t *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e70208)
Location: net/switchdev/switchdev.c:81
Inline: False
```
**Symbols:**

```
c0e70208-c0e702d4: switchdev_deferred_enqueue (STB_LOCAL)
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
In net/switchdev/switchdev.c (c000000000eb3330)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
c000000000eb3330-c000000000eb346c: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffffffe0008a3f3a)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffe0008a3f3a-ffffffe0008a401e: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffffffff81a418d0)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff81a418d0-ffffffff81a419a7: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffffffff819fe4c0)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff819fe4c0-ffffffff819fe597: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffffffff81aad780)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff81aad780-ffffffff81aad857: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
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
In net/switchdev/switchdev.c (ffffffff81ab9af0)
Location: net/switchdev/switchdev.c:81
Inline: True
```
**Symbols:**

```
ffffffff81ab9af0-ffffffff81ab9bc7: switchdev_deferred_enqueue.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
