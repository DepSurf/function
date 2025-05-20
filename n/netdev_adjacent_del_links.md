# Function: <code>netdev_adjacent_del_links</code>

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
In net/core/dev.c (ffffffff81718730)
Location: net/core/dev.c:5608
Inline: True
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
In net/core/dev.c (ffffffff81780f0f)
Location: net/core/dev.c:5999
Inline: True
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
In net/core/dev.c (ffffffff817ae45f)
Location: net/core/dev.c:6143
Inline: True
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
In net/core/dev.c (ffffffff817ccdd3)
Location: net/core/dev.c:6352
Inline: True
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
In net/core/dev.c (ffffffff81846734)
Location: net/core/dev.c:6507
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
In net/core/dev.c (ffffffff8188fe1c)
Location: net/core/dev.c:6643
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
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
In net/core/dev.c (ffffffff818b0787)
Location: net/core/dev.c:7218
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
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
In net/core/dev.c (ffffffff818fd4cf)
Location: net/core/dev.c:7228
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
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
In net/core/dev.c (ffffffff8192faf9)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netdev_adjacent_del_links(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a024b0)
Location: net/core/dev.c:7949
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81a024b0-ffffffff81a02610: netdev_adjacent_del_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_adjacent_del_links(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02cb0)
Location: net/core/dev.c:8194
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81a02cb0-ffffffff81a02e10: netdev_adjacent_del_links (STB_LOCAL)
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
In net/core/dev.c (ffffffff819ed548)
Location: net/core/dev.c:8453
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
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
In net/core/dev.c (ffffffff81a9e768)
Location: net/core/dev.c:8443
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c17446)
Location: net/core/dev.c:8210
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc8446)
Location: net/core/dev.c:8196
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e387fb)
Location: net/core/dev.c:8201
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef6900)
Location: net/core/dev.c:8319
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
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
In net/core/dev.c (ffff800010bccfbc)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce8a08)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caadb0)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007576ea)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
```
</details>
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
In net/core/dev.c (ffffffff818cfaf9)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889c19)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920af9)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
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
In net/core/dev.c (ffffffff81942889)
Location: net/core/dev.c:7536
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
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
</ul>
