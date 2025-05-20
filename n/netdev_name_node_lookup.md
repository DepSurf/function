# Function: <code>netdev_name_node_lookup</code>

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
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:275
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff81a01e50-ffffffff81a01ec5: netdev_name_node_lookup (STB_LOCAL)
ffffffff81a0ee2c-ffffffff81a0ee38: netdev_name_node_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:278
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff81a02490-ffffffff81a02505: netdev_name_node_lookup (STB_LOCAL)
ffffffff81c31120-ffffffff81c3112c: netdev_name_node_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:280
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff819e9000-ffffffff819e9074: netdev_name_node_lookup (STB_LOCAL)
ffffffff81c23429-ffffffff81c23435: netdev_name_node_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:282
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff81a99e30-ffffffff81a99ea4: netdev_name_node_lookup (STB_LOCAL)
ffffffff81d35fa6-ffffffff81d35fb2: netdev_name_node_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:297
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff81c13e10-ffffffff81c13e8b: netdev_name_node_lookup (STB_LOCAL)
ffffffff81f0286d-ffffffff81f02879: netdev_name_node_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc4480)
Location: net/core/dev.c:297
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff81dc4480-ffffffff81dc4503: netdev_name_node_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38ed4)
Location: net/core/dev.c:295
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff81e344e0-ffffffff81e34563: netdev_name_node_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct netdev_name_node *netdev_name_node_lookup(struct net *net, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef7172)
Location: net/core/dev.c:296
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
Direct callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff81ef1ec0-ffffffff81ef1f43: netdev_name_node_lookup (STB_LOCAL)
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
