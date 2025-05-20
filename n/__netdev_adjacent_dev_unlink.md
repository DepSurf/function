# Function: <code>__netdev_adjacent_dev_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __netdev_adjacent_dev_unlink(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716150)
Location: net/core/dev.c:5323
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81716150-ffffffff81716185: __netdev_adjacent_dev_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __netdev_adjacent_dev_unlink(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e060)
Location: net/core/dev.c:5713
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff8177e060-ffffffff8177e095: __netdev_adjacent_dev_unlink (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
