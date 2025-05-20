# Function: <code>tcf_del_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81748b1c)
Location: net/sched/act_api.c:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b5abe)
Location: net/sched/act_api.c:829
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e54c4)
Location: net/sched/act_api.c:888
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81804ff0)
Location: net/sched/act_api.c:960
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81883d10)
Location: net/sched/act_api.c:976
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d7883)
Location: net/sched/act_api.c:1031
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81903bce)
Location: net/sched/act_api.c:1225
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81964d4a)
Location: net/sched/act_api.c:1241
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199b8be)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_del_notify(struct net *net, struct nlmsghdr *n, struct tc_action **actions, u32 portid, size_t attr_size, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a74920)
Location: net/sched/act_api.c:1337
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81a74920-ffffffff81a74a82: tcf_del_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_del_notify(struct net *net, struct nlmsghdr *n, struct tc_action **actions, u32 portid, size_t attr_size, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7d720)
Location: net/sched/act_api.c:1388
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81a7d720-ffffffff81a7d882: tcf_del_notify (STB_LOCAL)
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
In net/sched/act_api.c (ffffffff81a666b4)
Location: net/sched/act_api.c:1398
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_del_notify(struct net *net, struct nlmsghdr *n, struct tc_action **actions, u32 portid, size_t attr_size, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1f730)
Location: net/sched/act_api.c:1405
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81b1f730-ffffffff81b1f957: tcf_del_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_del_notify(struct net *net, struct nlmsghdr *n, struct tc_action **actions, u32 portid, size_t attr_size, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca7590)
Location: net/sched/act_api.c:1851
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81ca7590-ffffffff81ca77c5: tcf_del_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_del_notify(struct net *net, struct nlmsghdr *n, struct tc_action **actions, u32 portid, size_t attr_size, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e642d0)
Location: net/sched/act_api.c:1877
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81e642d0-ffffffff81e64505: tcf_del_notify (STB_LOCAL)
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
In net/sched/act_api.c (ffffffff81ec0678)
Location: net/sched/act_api.c:1874
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
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
In net/sched/act_api.c (ffffffff81f83ab0)
Location: net/sched/act_api.c:1936
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c48af4)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d59afc)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d4616c)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b63e4)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193b72e)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f522e)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198c8be)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819af14e)
Location: net/sched/act_api.c:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
