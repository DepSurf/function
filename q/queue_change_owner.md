# Function: <code>queue_change_owner</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81966cae)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int queue_change_owner(struct net_device *ndev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a380e0)
Location: net/core/net-sysfs.c:1665
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81a380e0-ffffffff81a3820a: queue_change_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int queue_change_owner(struct net_device *ndev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a3a330)
Location: net/core/net-sysfs.c:1716
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81a3a330-ffffffff81a3a45a: queue_change_owner (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81a23782)
Location: net/core/net-sysfs.c:1732
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81ad7dae)
Location: net/core/net-sysfs.c:1787
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81c58b21)
Location: net/core/net-sysfs.c:1795
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81e0ea01)
Location: net/core/net-sysfs.c:1795
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81e81e41)
Location: net/core/net-sysfs.c:1823
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81f42e11)
Location: net/core/net-sysfs.c:1835
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffff800010c0c438)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (c0d24954)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (c000000000cf77f0)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffe00078978e)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81906c7e)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff818c0a8e)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81957cae)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
In net/core/net-sysfs.c (ffffffff81979d8e)
Location: net/core/net-sysfs.c:1634
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_change_owner
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
