# Function: <code>nexthop_notify</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:335
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff819d3b80-ffffffff819d3d20: nexthop_notify (STB_LOCAL)
ffffffff819d5f7f-ffffffff819d5f92: nexthop_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0a6f0)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81a0a6f0-ffffffff81a0a889: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afb9a0)
Location: net/ipv4/nexthop.c:362
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_add
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81afb9a0-ffffffff81afbb3d: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09070)
Location: net/ipv4/nexthop.c:490
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81b09070-ffffffff81b0920d: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af7200)
Location: net/ipv4/nexthop.c:840
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81af7200-ffffffff81af73b4: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:840
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81bb6ba0-ffffffff81bb6d66: nexthop_notify (STB_LOCAL)
ffffffff81d3e1b9-ffffffff81d3e1f8: nexthop_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:841
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81d4a800-ffffffff81d4a9f3: nexthop_notify (STB_LOCAL)
ffffffff81f0aa97-ffffffff81f0aad6: nexthop_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:841
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f13ec0-ffffffff81f140b3: nexthop_notify (STB_LOCAL)
ffffffff820b234c-ffffffff820b238b: nexthop_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:841
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f73b90-ffffffff81f73d85: nexthop_notify (STB_LOCAL)
ffffffff821334fc-ffffffff8213353b: nexthop_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:841
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff8203a380-ffffffff8203a575: nexthop_notify (STB_LOCAL)
ffffffff82214f08-ffffffff82214f47: nexthop_notify.cold (STB_LOCAL)
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
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc3ca0)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffff800010cc3ca0-ffff800010cc3e48: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcf17c)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
c0dcf17c-c0dcf324: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000ddfa30)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
c000000000ddfa30-c000000000ddfc78: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000818e56)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffe000818e56-ffffffe000818fb0: nexthop_notify (STB_LOCAL)
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
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819aa490)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff819aa490-ffffffff819aa629: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81963f50)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81963f50-ffffffff819640e9: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a14d30)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81a14d30-ffffffff81a14ec9: nexthop_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nexthop_notify(int event, struct nexthop *nh, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a1f740)
Location: net/ipv4/nexthop.c:337
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81a1f740-ffffffff81a1f8d9: nexthop_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
