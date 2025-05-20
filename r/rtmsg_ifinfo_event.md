# Function: <code>rtmsg_ifinfo_event</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e69ae)
Location: net/core/rtnetlink.c:2904
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff817e6910-ffffffff817e6955: rtmsg_ifinfo_event.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8186188e)
Location: net/core/rtnetlink.c:3135
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81861810-ffffffff81861855: rtmsg_ifinfo_event.part.29 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818ad44e)
Location: net/core/rtnetlink.c:3291
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff818ad3d0-ffffffff818ad41e: rtmsg_ifinfo_event.part.34 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818d16ae)
Location: net/core/rtnetlink.c:3434
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff818d1630-ffffffff818d167e: rtmsg_ifinfo_event.part.35 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff8191e570)
Location: net/core/rtnetlink.c:3495
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff8191e4f0-ffffffff8191e53e: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81950ba0)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81950b20-ffffffff81950b6e: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a219a4)
Location: net/core/rtnetlink.c:3729
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21de4)
Location: net/core/rtnetlink.c:3821
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
In net/core/rtnetlink.c (ffffffff81a0911d)
Location: net/core/rtnetlink.c:3819
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81abb5ed)
Location: net/core/rtnetlink.c:3840
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c35e4f)
Location: net/core/rtnetlink.c:3931
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de940f)
Location: net/core/rtnetlink.c:3976
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
In net/core/rtnetlink.c (ffffffff81e5ac5a)
Location: net/core/rtnetlink.c:4065
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
In net/core/rtnetlink.c (ffffffff81f1a01a)
Location: net/core/rtnetlink.c:4105
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
In net/core/rtnetlink.c (ffff800010bf2710)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffff800010bf2618-ffff800010bf26b0: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (c0d0b010)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
c0d0af04-c0d0af5c: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (c000000000cd76c0)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
c000000000cd7590-c000000000cd7600: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffe0007741f0)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffe000774136-ffffffe0007741ac: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818f0b70)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff818f0af0-ffffffff818f0b3e: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818aa9b0)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff818aa930-ffffffff818aa97e: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81941ba0)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81941b20-ffffffff81941b6e: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff819634a0)
Location: net/core/rtnetlink.c:3526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81963420-ffffffff8196346e: rtmsg_ifinfo_event.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
