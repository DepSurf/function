# Function: <code>netdev_unbind_all_sb_channels</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b33c0)
Location: net/core/dev.c:2524
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818b33c0-ffffffff818b3416: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fc290)
Location: net/core/dev.c:2534
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818fc290-ffffffff818fc2e6: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192e870)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff8192e870-ffffffff8192e8c6: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a033d5)
Location: net/core/dev.c:2812
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a036a5)
Location: net/core/dev.c:2837
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
In net/core/dev.c (ffffffff819e8948)
Location: net/core/dev.c:2905
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
In net/core/dev.c (ffffffff81a99988)
Location: net/core/dev.c:2780
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
In net/core/dev.c (ffffffff81c10c68)
Location: net/core/dev.c:2757
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
In net/core/dev.c (ffffffff81dc0a88)
Location: net/core/dev.c:2742
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
In net/core/dev.c (ffffffff81e30608)
Location: net/core/dev.c:2770
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
In net/core/dev.c (ffffffff81eeefa8)
Location: net/core/dev.c:2773
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc9e00)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffff800010bc9e00-ffff800010bc9e5c: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce9628)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
c0ce9628-c0ce967c: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca7d60)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
c000000000ca7d60-c000000000ca7ddc: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000759040)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffe000759040-ffffffe000759096: netdev_unbind_all_sb_channels (STB_LOCAL)
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
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ce870)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818ce870-ffffffff818ce8c6: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81888990)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81888990-ffffffff818889e6: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191f870)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff8191f870-ffffffff8191f8c6: netdev_unbind_all_sb_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819415d0)
Location: net/core/dev.c:2452
Inline: False
Direct callers:
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff819415d0-ffffffff81941626: netdev_unbind_all_sb_channels (STB_LOCAL)
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
