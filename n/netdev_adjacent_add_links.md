# Function: <code>netdev_adjacent_add_links</code>

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
In net/core/dev.c (ffffffff817187f2)
Location: net/core/dev.c:5583
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
In net/core/dev.c (ffffffff81781063)
Location: net/core/dev.c:5974
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
In net/core/dev.c (ffffffff817ae5b3)
Location: net/core/dev.c:6118
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
In net/core/dev.c (ffffffff817ccee5)
Location: net/core/dev.c:6327
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
In net/core/dev.c (ffffffff81846891)
Location: net/core/dev.c:6482
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
In net/core/dev.c (ffffffff8188fe75)
Location: net/core/dev.c:6618
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
In net/core/dev.c (ffffffff818b07e3)
Location: net/core/dev.c:7193
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
In net/core/dev.c (ffffffff818fd528)
Location: net/core/dev.c:7203
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
In net/core/dev.c (ffffffff8192fb51)
Location: net/core/dev.c:7511
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
void netdev_adjacent_add_links(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02ae0)
Location: net/core/dev.c:7924
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81a02ae0-ffffffff81a02c79: netdev_adjacent_add_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_adjacent_add_links(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03370)
Location: net/core/dev.c:8169
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81a03370-ffffffff81a03509: netdev_adjacent_add_links (STB_LOCAL)
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
In net/core/dev.c (ffffffff819ed804)
Location: net/core/dev.c:8428
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
In net/core/dev.c (ffffffff81a9ea24)
Location: net/core/dev.c:8418
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
In net/core/dev.c (ffffffff81c17750)
Location: net/core/dev.c:8185
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
In net/core/dev.c (ffffffff81dc8760)
Location: net/core/dev.c:8171
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
In net/core/dev.c (ffffffff81e38a4c)
Location: net/core/dev.c:8176
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
In net/core/dev.c (ffffffff81ef6c41)
Location: net/core/dev.c:8294
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
In net/core/dev.c (ffff800010bccffc)
Location: net/core/dev.c:7511
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
In net/core/dev.c (c0ce8aac)
Location: net/core/dev.c:7511
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
In net/core/dev.c (c000000000caae08)
Location: net/core/dev.c:7511
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
In net/core/dev.c (ffffffe000757720)
Location: net/core/dev.c:7511
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
In net/core/dev.c (ffffffff818cfb51)
Location: net/core/dev.c:7511
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
In net/core/dev.c (ffffffff81889c71)
Location: net/core/dev.c:7511
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
In net/core/dev.c (ffffffff81920b51)
Location: net/core/dev.c:7511
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
In net/core/dev.c (ffffffff819428e1)
Location: net/core/dev.c:7511
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
