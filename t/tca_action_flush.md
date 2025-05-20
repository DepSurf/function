# Function: <code>tca_action_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81747110)
Location: net/sched/act_api.c:776
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81747110-ffffffff817473f8: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b4360)
Location: net/sched/act_api.c:757
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff817b4360-ffffffff817b45ce: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e3c10)
Location: net/sched/act_api.c:819
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff817e3c10-ffffffff817e3e7c: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81803560)
Location: net/sched/act_api.c:891
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81803560-ffffffff818037cf: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818819e0)
Location: net/sched/act_api.c:907
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff818819e0-ffffffff81881c55: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (ffffffff818d5a30)
Location: net/sched/act_api.c:953
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff818d5a30-ffffffff818d5d1c: tca_action_flush.isra.28 (STB_LOCAL)
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
In net/sched/act_api.c (ffffffff81903d0a)
Location: net/sched/act_api.c:1118
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
In net/sched/act_api.c (ffffffff81964e86)
Location: net/sched/act_api.c:1134
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
In net/sched/act_api.c (ffffffff8199b9fa)
Location: net/sched/act_api.c:1136
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
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a73720)
Location: net/sched/act_api.c:1229
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81a73720-ffffffff81a73a1b: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7c320)
Location: net/sched/act_api.c:1280
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81a7c320-ffffffff81a7c61b: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a64f60)
Location: net/sched/act_api.c:1290
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81a64f60-ffffffff81a652aa: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1e230)
Location: net/sched/act_api.c:1299
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81b1e230-ffffffff81b1e570: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca5c20)
Location: net/sched/act_api.c:1655
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81ca5c20-ffffffff81ca5f7f: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e63cd0)
Location: net/sched/act_api.c:1681
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81e63cd0-ffffffff81e6402b: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebfd60)
Location: net/sched/act_api.c:1678
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81ebfd60-ffffffff81ec00bb: tca_action_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f82f10)
Location: net/sched/act_api.c:1706
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81f82f10-ffffffff81f8326e: tca_action_flush (STB_LOCAL)
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
In net/sched/act_api.c (ffff800010c48bf4)
Location: net/sched/act_api.c:1136
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tca_action_flush(struct net *net, struct nlattr *nla, struct nlmsghdr *n, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d58800)
Location: net/sched/act_api.c:1136
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
c0d58800-c0d58ab4: tca_action_flush (STB_LOCAL)
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
In net/sched/act_api.c (c000000000d462c4)
Location: net/sched/act_api.c:1136
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
In net/sched/act_api.c (ffffffe0007b64dc)
Location: net/sched/act_api.c:1136
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
In net/sched/act_api.c (ffffffff8193b86a)
Location: net/sched/act_api.c:1136
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
In net/sched/act_api.c (ffffffff818f536a)
Location: net/sched/act_api.c:1136
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
In net/sched/act_api.c (ffffffff8198c9fa)
Location: net/sched/act_api.c:1136
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
In net/sched/act_api.c (ffffffff819af28a)
Location: net/sched/act_api.c:1136
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
</ul>
