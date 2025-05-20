# Function: <code>call_nexthop_notifiers</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afb075)
Location: net/ipv4/nexthop.c:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__remove_nexthop_fib
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_nexthop_notifiers(struct net *net, enum nexthop_event_type event_type, struct nexthop *nh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0a220)
Location: net/ipv4/nexthop.c:131
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81b0a220-ffffffff81b0a389: call_nexthop_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_nexthop_notifiers(struct net *net, enum nexthop_event_type event_type, struct nexthop *nh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af5d50)
Location: net/ipv4/nexthop.c:222
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81af5d50-ffffffff81af5fbd: call_nexthop_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int call_nexthop_notifiers(struct net *net, enum nexthop_event_type event_type, struct nexthop *nh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:222
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81bb8490-ffffffff81bb85ba: call_nexthop_notifiers (STB_LOCAL)
ffffffff81d3e467-ffffffff81d3e47c: call_nexthop_notifiers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int call_nexthop_notifiers(struct net *net, enum nexthop_event_type event_type, struct nexthop *nh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:223
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81d4c300-ffffffff81d4c43e: call_nexthop_notifiers (STB_LOCAL)
ffffffff81f0ad47-ffffffff81f0ad5c: call_nexthop_notifiers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int call_nexthop_notifiers(struct net *net, enum nexthop_event_type event_type, struct nexthop *nh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:223
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f15b00-ffffffff81f15c3e: call_nexthop_notifiers (STB_LOCAL)
ffffffff820b25d0-ffffffff820b25e5: call_nexthop_notifiers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int call_nexthop_notifiers(struct net *net, enum nexthop_event_type event_type, struct nexthop *nh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:223
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f75790-ffffffff81f758d0: call_nexthop_notifiers (STB_LOCAL)
ffffffff82133788-ffffffff8213379d: call_nexthop_notifiers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int call_nexthop_notifiers(struct net *net, enum nexthop_event_type event_type, struct nexthop *nh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:223
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff8203bf60-ffffffff8203c0a0: call_nexthop_notifiers (STB_LOCAL)
ffffffff82215194-ffffffff822151a9: call_nexthop_notifiers.cold (STB_LOCAL)
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
