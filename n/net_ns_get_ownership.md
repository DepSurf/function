# Function: <code>net_ns_get_ownership</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81886ba0)
Location: net/core/net_namespace.c:461
Inline: True
Direct callers:
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81886ba0-ffffffff81886c00: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a7290)
Location: net/core/net_namespace.c:461
Inline: True
Direct callers:
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff818a7290-ffffffff818a72f0: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f29d0)
Location: net/core/net_namespace.c:499
Inline: True
Direct callers:
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff818f29d0-ffffffff818f2a38: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81924930)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81924930-ffffffff81924998: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f7f40)
Location: net/core/net_namespace.c:507
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff819f7f40-ffffffff819f7fa8: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f79a0)
Location: net/core/net_namespace.c:508
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff819f79a0-ffffffff819f7a08: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819ddb20)
Location: net/core/net_namespace.c:499
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff819ddb20-ffffffff819ddb88: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8dda0)
Location: net/core/net_namespace.c:499
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81a8dda0-ffffffff81a8de08: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c039d0)
Location: net/core/net_namespace.c:498
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81c039d0-ffffffff81c03a50: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db3060)
Location: net/core/net_namespace.c:517
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81db3060-ffffffff81db30e0: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e23630)
Location: net/core/net_namespace.c:518
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81e23630-ffffffff81e236b0: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee1590)
Location: net/core/net_namespace.c:522
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81ee1590-ffffffff81ee1610: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc03b8)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffff800010bc03b8-ffff800010bc0440: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdbe60)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
c0cdbe60-c0cdbec4: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c99b80)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
c000000000c99b80-c000000000c99c5c: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074defe)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffe00074defe-ffffffe00074df7a: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c4930)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff818c4930-ffffffff818c4998: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187e870)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff8187e870-ffffffff8187e8d8: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81915930)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81915930-ffffffff81915998: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void net_ns_get_ownership(const struct net *net, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81936b20)
Location: net/core/net_namespace.c:501
Inline: True
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:netdev_queue_get_ownership
  - net/core/net-sysfs.c:rx_queue_get_ownership
```
**Symbols:**

```
ffffffff81936b20-ffffffff81936b88: net_ns_get_ownership (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
