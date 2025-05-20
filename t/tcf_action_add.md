# Function: <code>tcf_action_add</code>

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
In net/sched/act_api.c (ffffffff81748d36)
Location: net/sched/act_api.c:947
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
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
In net/sched/act_api.c (ffffffff817b5db7)
Location: net/sched/act_api.c:927
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
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
In net/sched/act_api.c (ffffffff817e57ca)
Location: net/sched/act_api.c:986
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
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
In net/sched/act_api.c (ffffffff818052d0)
Location: net/sched/act_api.c:1058
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
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
In net/sched/act_api.c (ffffffff81883fed)
Location: net/sched/act_api.c:1074
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
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
In net/sched/act_api.c (ffffffff818d7b3a)
Location: net/sched/act_api.c:1139
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81904190)
Location: net/sched/act_api.c:1332
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81904190-ffffffff81904310: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819652d0)
Location: net/sched/act_api.c:1348
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff819652d0-ffffffff81965449: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199be60)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff8199be60-ffffffff8199c00a: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a74cc0)
Location: net/sched/act_api.c:1444
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81a74cc0-ffffffff81a74e66: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7dac0)
Location: net/sched/act_api.c:1495
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81a7dac0-ffffffff81a7dc66: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a668c0)
Location: net/sched/act_api.c:1505
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81a668c0-ffffffff81a66a9a: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1fd40)
Location: net/sched/act_api.c:1506
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81b1fd40-ffffffff81b1ff5b: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca7bf0)
Location: net/sched/act_api.c:1952
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81ca7bf0-ffffffff81ca7e19: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e649a0)
Location: net/sched/act_api.c:1978
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81e649a0-ffffffff81e64bc9: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ec08f0)
Location: net/sched/act_api.c:1975
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81ec08f0-ffffffff81ec0b1d: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f83540)
Location: net/sched/act_api.c:2052
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81f83540-ffffffff81f8377c: tcf_action_add (STB_LOCAL)
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
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c48fc0)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffff800010c48fc0-ffff800010c49178: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d59df4)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
c0d59df4-c0d59fa8: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d46790)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
c000000000d46790-c000000000d469a0: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b6806)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffe0007b6806-ffffffe0007b6956: tcf_action_add (STB_LOCAL)
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
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193bcd0)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff8193bcd0-ffffffff8193be7a: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f57d0)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff818f57d0-ffffffff818f597a: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198ce60)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff8198ce60-ffffffff8198d00a: tcf_action_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_action_add(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819af6f0)
Location: net/sched/act_api.c:1351
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff819af6f0-ffffffff819af89a: tcf_action_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int ovr</code>
</li>
</ul>
</details>
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
