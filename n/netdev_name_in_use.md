# Function: <code>netdev_name_in_use</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool netdev_name_in_use(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c17b02)
Location: net/core/dev.c:321
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
```
**Symbols:**

```
ffffffff81c13e90-ffffffff81c13eae: netdev_name_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool netdev_name_in_use(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc8b22)
Location: net/core/dev.c:321
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
```
**Symbols:**

```
ffffffff81dc4520-ffffffff81dc453e: netdev_name_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool netdev_name_in_use(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38ed4)
Location: net/core/dev.c:319
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
```
**Symbols:**

```
ffffffff81e34580-ffffffff81e3459e: netdev_name_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool netdev_name_in_use(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef7124)
Location: net/core/dev.c:320
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
```
**Symbols:**

```
ffffffff81ef1f60-ffffffff81ef1f7e: netdev_name_in_use (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
