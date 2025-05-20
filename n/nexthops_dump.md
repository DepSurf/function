# Function: <code>nexthops_dump</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nexthops_dump(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0acb0)
Location: net/ipv4/nexthop.c:2148
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:register_nexthop_notifier
```
**Symbols:**

```
ffffffff81b0acb0-ffffffff81b0adf4: nexthops_dump (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81af5ff4)
Location: net/ipv4/nexthop.c:3565
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:register_nexthop_notifier
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nexthops_dump(struct net *net, struct notifier_block *nb, enum nexthop_event_type event_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb82f0)
Location: net/ipv4/nexthop.c:3594
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
```
**Symbols:**

```
ffffffff81bb82f0-ffffffff81bb83d1: nexthops_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nexthops_dump(struct net *net, struct notifier_block *nb, enum nexthop_event_type event_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4c130)
Location: net/ipv4/nexthop.c:3594
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
```
**Symbols:**

```
ffffffff81d4c130-ffffffff81d4c227: nexthops_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nexthops_dump(struct net *net, struct notifier_block *nb, enum nexthop_event_type event_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f15900)
Location: net/ipv4/nexthop.c:3594
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
```
**Symbols:**

```
ffffffff81f15900-ffffffff81f159f7: nexthops_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nexthops_dump(struct net *net, struct notifier_block *nb, enum nexthop_event_type event_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f75590)
Location: net/ipv4/nexthop.c:3580
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
```
**Symbols:**

```
ffffffff81f75590-ffffffff81f75687: nexthops_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nexthops_dump(struct net *net, struct notifier_block *nb, enum nexthop_event_type event_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203bd60)
Location: net/ipv4/nexthop.c:3597
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
```
**Symbols:**

```
ffffffff8203bd60-ffffffff8203be57: nexthops_dump (STB_LOCAL)
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
