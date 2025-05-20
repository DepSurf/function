# Function: <code>netdev_name_node_lookup_rcu</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup_rcu(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:287
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_by_name
```
**Symbols:**

```
ffffffff81a02090-ffffffff81a02108: netdev_name_node_lookup_rcu (STB_LOCAL)
ffffffff81a0ee44-ffffffff81a0ee50: netdev_name_node_lookup_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup_rcu(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:290
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
```
**Symbols:**

```
ffffffff81a026d0-ffffffff81a02748: netdev_name_node_lookup_rcu (STB_LOCAL)
ffffffff81c31138-ffffffff81c31144: netdev_name_node_lookup_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup_rcu(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:292
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
```
**Symbols:**

```
ffffffff819e9240-ffffffff819e92b7: netdev_name_node_lookup_rcu (STB_LOCAL)
ffffffff81c23441-ffffffff81c2344d: netdev_name_node_lookup_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup_rcu(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:294
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
```
**Symbols:**

```
ffffffff81a9a070-ffffffff81a9a0e7: netdev_name_node_lookup_rcu (STB_LOCAL)
ffffffff81d35fbe-ffffffff81d35fca: netdev_name_node_lookup_rcu.cold (STB_LOCAL)
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
In net/core/dev.c (ffffffff81c0c1ca)
Location: net/core/dev.c:309
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
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
In net/core/dev.c (ffffffff81dc49da)
Location: net/core/dev.c:309
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
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
In net/core/dev.c (ffffffff81e361ba)
Location: net/core/dev.c:307
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:netdev_get_by_name
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
In net/core/dev.c (ffffffff81ef447a)
Location: net/core/dev.c:308
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:netdev_get_by_name
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
