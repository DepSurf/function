# Function: <code>qdisc_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int qdisc_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, u32 clid, struct Qdisc *old, struct Qdisc *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817440e0)
Location: net/sched/sch_api.c:1399
Inline: False
Direct callers:
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff817440e0-ffffffff8174420f: qdisc_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int qdisc_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, u32 clid, struct Qdisc *old, struct Qdisc *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b1100)
Location: net/sched/sch_api.c:1401
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff817b1100-ffffffff817b122c: qdisc_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int qdisc_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, u32 clid, struct Qdisc *old, struct Qdisc *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e0880)
Location: net/sched/sch_api.c:1419
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff817e0880-ffffffff817e09ac: qdisc_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int qdisc_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, u32 clid, struct Qdisc *old, struct Qdisc *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817ffd60)
Location: net/sched/sch_api.c:1425
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff817ffd60-ffffffff817ffe6b: qdisc_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int qdisc_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, u32 clid, struct Qdisc *old, struct Qdisc *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187db00)
Location: net/sched/sch_api.c:848
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff8187db00-ffffffff8187dc0b: qdisc_notify (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff818d0360)
Location: net/sched/sch_api.c:878
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff818d0360-ffffffff818d0479: qdisc_notify.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fb5b0)
Location: net/sched/sch_api.c:965
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff818fb5b0-ffffffff818fb6c6: qdisc_notify.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195b010)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff8195b010-ffffffff8195b129: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff819914c0)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff819914c0-ffffffff819915d9: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a694d0)
Location: net/sched/sch_api.c:965
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a694d0-ffffffff81a695d0: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a71c10)
Location: net/sched/sch_api.c:967
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a71c10-ffffffff81a71d10: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a5a5f0)
Location: net/sched/sch_api.c:967
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a5a5f0-ffffffff81a5a6f0: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b13750)
Location: net/sched/sch_api.c:973
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81b13750-ffffffff81b13850: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9a150)
Location: net/sched/sch_api.c:973
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81c9a150-ffffffff81c9a260: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e564c0)
Location: net/sched/sch_api.c:992
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81e564c0-ffffffff81e565d0: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb2af0)
Location: net/sched/sch_api.c:1006
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81eb2af0-ffffffff81eb2c09: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f755a0)
Location: net/sched/sch_api.c:1032
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81f755a0-ffffffff81f75712: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3d938)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffff800010c3d938-ffff800010c3da68: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int qdisc_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, u32 clid, struct Qdisc *old, struct Qdisc *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4f45c)
Location: net/sched/sch_api.c:956
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
c0d4f45c-c0d4f588: qdisc_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (c000000000d373a0)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
c000000000d373a0-c000000000d37560: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007adcb8)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffe0007adcb8-ffffffe0007addaa: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81931330)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff81931330-ffffffff81931449: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818eae30)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff818eae30-ffffffff818eaf49: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff819824c0)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff819824c0-ffffffff819825d9: qdisc_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a4a00)
Location: net/sched/sch_api.c:956
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:notify_and_destroy
```
**Symbols:**

```
ffffffff819a4a00-ffffffff819a4b19: qdisc_notify.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
