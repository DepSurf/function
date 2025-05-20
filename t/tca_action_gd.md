# Function: <code>tca_action_gd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81748840)
Location: net/sched/act_api.c:880
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81748840-ffffffff81748c40: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b5960)
Location: net/sched/act_api.c:860
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff817b5960-ffffffff817b5ca7: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e5360)
Location: net/sched/act_api.c:919
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff817e5360-ffffffff817e56b9: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81804e80)
Location: net/sched/act_api.c:991
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81804e80-ffffffff818051d5: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81883ba0)
Location: net/sched/act_api.c:1007
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81883ba0-ffffffff81883efe: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d75f0)
Location: net/sched/act_api.c:1065
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff818d75f0-ffffffff818d7a3a: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819039c0)
Location: net/sched/act_api.c:1259
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff819039c0-ffffffff81904186: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1275
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81964b70-ffffffff819652cb: tca_action_gd (STB_LOCAL)
ffffffff819656cb-ffffffff819656f9: tca_action_gd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199b6e0)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff8199b6e0-ffffffff8199be51: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a74a90)
Location: net/sched/act_api.c:1371
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81a74a90-ffffffff81a74cb4: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7d890)
Location: net/sched/act_api.c:1422
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81a7d890-ffffffff81a7dab4: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a66470)
Location: net/sched/act_api.c:1432
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81a66470-ffffffff81a668bd: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1f960)
Location: net/sched/act_api.c:1437
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81b1f960-ffffffff81b1fd40: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca77d0)
Location: net/sched/act_api.c:1883
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81ca77d0-ffffffff81ca7be4: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e64520)
Location: net/sched/act_api.c:1909
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81e64520-ffffffff81e64981: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ec0390)
Location: net/sched/act_api.c:1906
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81ec0390-ffffffff81ec08d2: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f83790)
Location: net/sched/act_api.c:1965
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff81f83790-ffffffff81f83d7d: tca_action_gd (STB_LOCAL)
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
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c48920)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffff800010c48920-ffff800010c48fbc: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d59920)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
c0d59920-c0d59df4: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d45ef0)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
c000000000d45ef0-c000000000d46788: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b6224)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffe0007b6224-ffffffe0007b6806: tca_action_gd (STB_LOCAL)
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
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193b550)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff8193b550-ffffffff8193bcc1: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f5050)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff818f5050-ffffffff818f57c1: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198c6e0)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff8198c6e0-ffffffff8198ce51: tca_action_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tca_action_gd(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819aef70)
Location: net/sched/act_api.c:1278
Inline: False
Direct callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff819aef70-ffffffff819af6e1: tca_action_gd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
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
