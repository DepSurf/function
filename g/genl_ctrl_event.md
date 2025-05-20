# Function: <code>genl_ctrl_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int genl_ctrl_event(int event, struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817501d0)
Location: net/netlink/genetlink.c:944
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff817501d0-ffffffff81750541: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int genl_ctrl_event(int event, struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817bc2c0)
Location: net/netlink/genetlink.c:939
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff817bc2c0-ffffffff817bc606: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817ebbd0)
Location: net/netlink/genetlink.c:890
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff817ebbd0-ffffffff817ebf16: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8180bb20)
Location: net/netlink/genetlink.c:893
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8180bb20-ffffffff8180be40: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8188aab0)
Location: net/netlink/genetlink.c:894
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8188aab0-ffffffff8188add0: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818de0e0)
Location: net/netlink/genetlink.c:896
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff818de0e0-ffffffff818de400: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8190aaa0)
Location: net/netlink/genetlink.c:897
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8190aaa0-ffffffff8190adc0: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8196bea0-ffffffff8196c1b2: genl_ctrl_event (STB_LOCAL)
ffffffff8196cece-ffffffff8196cefb: genl_ctrl_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819a2850)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff819a2850-ffffffff819a2b69: genl_ctrl_event (STB_LOCAL)
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
In net/netlink/genetlink.c (ffffffff81a7cf00)
Location: net/netlink/genetlink.c:1001
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_mc_groups
```
**Symbols:**

```
ffffffff81a7cf00-ffffffff81a7d071: genl_ctrl_event.isra.0 (STB_LOCAL)
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
In net/netlink/genetlink.c (ffffffff81a864b0)
Location: net/netlink/genetlink.c:1072
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_mc_groups
```
**Symbols:**

```
ffffffff81a864b0-ffffffff81a86628: genl_ctrl_event.isra.0 (STB_LOCAL)
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
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:1072
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a6f520-ffffffff81a6f848: genl_ctrl_event.isra.0 (STB_LOCAL)
ffffffff81c245f8-ffffffff81c24610: genl_ctrl_event.isra.0.cold (STB_LOCAL)
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
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:1064
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81b28ba0-ffffffff81b28ec8: genl_ctrl_event.isra.0 (STB_LOCAL)
ffffffff81d39592-ffffffff81d395aa: genl_ctrl_event.isra.0.cold (STB_LOCAL)
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
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:1064
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81cb1c70-ffffffff81cb1f7e: genl_ctrl_event.isra.0 (STB_LOCAL)
ffffffff81f05ce9-ffffffff81f05d01: genl_ctrl_event.isra.0.cold (STB_LOCAL)
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
In net/netlink/genetlink.c (ffffffff81e6fe40)
Location: net/netlink/genetlink.c:1331
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81e6fe40-ffffffff81e70167: genl_ctrl_event.isra.0 (STB_LOCAL)
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
In net/netlink/genetlink.c (ffffffff81ecbf50)
Location: net/netlink/genetlink.c:1333
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81ecbf50-ffffffff81ecc277: genl_ctrl_event.isra.0 (STB_LOCAL)
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
In net/netlink/genetlink.c (ffffffff81f8f470)
Location: net/netlink/genetlink.c:1472
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81f8f470-ffffffff81f8f7a0: genl_ctrl_event.isra.0 (STB_LOCAL)
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
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffff800010c51b10)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffff800010c51b10-ffff800010c51e54: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c0d611f8)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
c0d611f8-c0d6155c: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c000000000d505a0)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
c000000000d505a0-c000000000d50a3c: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffe0007bcc30)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffe0007bcc30-ffffffe0007bcea4: genl_ctrl_event (STB_LOCAL)
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
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819426c0)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff819426c0-ffffffff819429d9: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818fc1b0)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff818fc1b0-ffffffff818fc4c9: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81993850)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81993850-ffffffff81993b69: genl_ctrl_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int genl_ctrl_event(int event, const struct genl_family *family, const struct genl_multicast_group *grp, int grp_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819b6340)
Location: net/netlink/genetlink.c:924
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff819b6340-ffffffff819b6663: genl_ctrl_event (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct genl_family *family</code> ➡️ <code>const struct genl_family *family</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
