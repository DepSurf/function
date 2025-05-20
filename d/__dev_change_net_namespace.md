# Function: <code>__dev_change_net_namespace</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed3b0)
Location: net/core/dev.c:11134
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff819ed3b0-ffffffff819eda74: __dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:11141
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81d362a9-ffffffff81d362bd: __dev_change_net_namespace.cold (STB_LOCAL)
ffffffff81a9e5d0-ffffffff81a9eca0: __dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10924
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81f02a9e-ffffffff81f02ab3: __dev_change_net_namespace.cold (STB_LOCAL)
ffffffff81c17280-ffffffff81c17a45: __dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10928
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff820ab5c2-ffffffff820ab5d7: __dev_change_net_namespace.cold (STB_LOCAL)
ffffffff81dc8280-ffffffff81dc8a55: __dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10945
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8212cc39-ffffffff8212cc4e: __dev_change_net_namespace.cold (STB_LOCAL)
ffffffff81e38640-ffffffff81e38e09: __dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:11156
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8220e977-ffffffff8220e98c: __dev_change_net_namespace.cold (STB_LOCAL)
ffffffff81ef66e0-ffffffff81ef702f: __dev_change_net_namespace (STB_GLOBAL)
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
