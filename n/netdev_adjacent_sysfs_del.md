# Function: <code>netdev_adjacent_sysfs_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81715f50)
Location: net/core/dev.c:5171
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff81715f50-ffffffff81715fc6: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177de60)
Location: net/core/dev.c:5561
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
```
**Symbols:**

```
ffffffff8177de60-ffffffff8177ded6: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ab960)
Location: net/core/dev.c:5808
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff817ab960-ffffffff817ab9d6: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9fd0)
Location: net/core/dev.c:6015
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff817c9fd0-ffffffff817ca046: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818438f0)
Location: net/core/dev.c:6156
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff818438f0-ffffffff81843966: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188dca0)
Location: net/core/dev.c:6286
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff8188dca0-ffffffff8188dd16: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aeb30)
Location: net/core/dev.c:6861
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff818aeb30-ffffffff818aeba6: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fa420)
Location: net/core/dev.c:6871
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff818fa420-ffffffff818fa496: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192c560)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff8192c560-ffffffff8192c5d6: netdev_adjacent_sysfs_del (STB_LOCAL)
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
In net/core/dev.c (ffffffff81a0b5fa)
Location: net/core/dev.c:7472
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
In net/core/dev.c (ffffffff81a0cc9a)
Location: net/core/dev.c:7646
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
In net/core/dev.c (ffffffff819ed589)
Location: net/core/dev.c:7905
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
In net/core/dev.c (ffffffff81a9e7a9)
Location: net/core/dev.c:7895
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
In net/core/dev.c (ffffffff81c1748e)
Location: net/core/dev.c:7426
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
In net/core/dev.c (ffffffff81dc848e)
Location: net/core/dev.c:7412
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
In net/core/dev.c (ffffffff81e38843)
Location: net/core/dev.c:7417
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
In net/core/dev.c (ffffffff81ef6967)
Location: net/core/dev.c:7535
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
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
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc8b00)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffff800010bc8b00-ffff800010bc8b8c: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce4d50)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
c0ce4d50-c0ce4de0: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca5420)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
c000000000ca5420-c000000000ca54c0: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000755348)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffe000755348-ffffffe0007553aa: netdev_adjacent_sysfs_del (STB_LOCAL)
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
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cc560)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff818cc560-ffffffff818cc5d6: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818865f0)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff818865f0-ffffffff81886666: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191d560)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff8191d560-ffffffff8191d5d6: netdev_adjacent_sysfs_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netdev_adjacent_sysfs_del(struct net_device *dev, char *name, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193ea70)
Location: net/core/dev.c:7081
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
```
**Symbols:**

```
ffffffff8193ea70-ffffffff8193eae6: netdev_adjacent_sysfs_del (STB_LOCAL)
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
