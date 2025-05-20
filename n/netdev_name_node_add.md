# Function: <code>netdev_name_node_add</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_name_node_add(struct net *net, struct netdev_name_node *name_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a01f5f)
Location: net/core/dev.c:263
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff81a01cf0-ffffffff81a01d60: netdev_name_node_add (STB_LOCAL)
ffffffff81a0ee20-ffffffff81a0ee2c: netdev_name_node_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_name_node_add(struct net *net, struct netdev_name_node *name_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a0259f)
Location: net/core/dev.c:266
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff81a02170-ffffffff81a021e0: netdev_name_node_add (STB_LOCAL)
ffffffff81c31114-ffffffff81c31120: netdev_name_node_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_name_node_add(struct net *net, struct netdev_name_node *name_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819e910f)
Location: net/core/dev.c:268
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff819e8ea0-ffffffff819e8f0f: netdev_name_node_add (STB_LOCAL)
ffffffff81c2341d-ffffffff81c23429: netdev_name_node_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_name_node_add(struct net *net, struct netdev_name_node *name_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a99f3f)
Location: net/core/dev.c:270
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff81a99ba0-ffffffff81a99c0f: netdev_name_node_add (STB_LOCAL)
ffffffff81d35f85-ffffffff81d35f91: netdev_name_node_add.cold (STB_LOCAL)
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
In net/core/dev.c (ffffffff81c1ce91)
Location: net/core/dev.c:285
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
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
In net/core/dev.c (ffffffff81dcdef7)
Location: net/core/dev.c:285
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
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
In net/core/dev.c (ffffffff81e3eb07)
Location: net/core/dev.c:283
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
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
In net/core/dev.c (ffffffff81efd442)
Location: net/core/dev.c:284
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
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
