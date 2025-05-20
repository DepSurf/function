# Function: <code>__netdev_adjacent_dev_set</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a260)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff8192a260-ffffffff8192a2d1: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe0f0)
Location: net/core/dev.c:7800
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff819fe0f0-ffffffff819fe166: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fdc80)
Location: net/core/dev.c:7997
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff819fdc80-ffffffff819fdcf6: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e4540)
Location: net/core/dev.c:8256
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff819e4540-ffffffff819e45b1: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a95020)
Location: net/core/dev.c:8246
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff81a95020-ffffffff81a95091: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0b5c0)
Location: net/core/dev.c:7777
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff81c0b5c0-ffffffff81c0b642: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbb5e0)
Location: net/core/dev.c:7763
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff81dbb5e0-ffffffff81dbb662: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2bd70)
Location: net/core/dev.c:7768
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff81e2bd70-ffffffff81e2bdf2: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee9dd0)
Location: net/core/dev.c:7886
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff81ee9dd0-ffffffff81ee9e52: __netdev_adjacent_dev_set (STB_LOCAL)
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
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc6b60)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffff800010bc6b60-ffff800010bc6c0c: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce200c)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
c0ce200c-c0ce209c: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca17f0)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
c000000000ca17f0-c000000000ca187c: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007530ea)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffe0007530ea-ffffffe000753164: __netdev_adjacent_dev_set (STB_LOCAL)
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
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca260)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff818ca260-ffffffff818ca2d1: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818841a0)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff818841a0-ffffffff81884211: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b260)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff8191b260-ffffffff8191b2d1: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device *upper_dev, struct net_device *lower_dev, bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193c460)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff8193c460-ffffffff8193c4d1: __netdev_adjacent_dev_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
