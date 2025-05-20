# Function: <code>igmpv3_add_delrec</code>

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
In net/ipv4/igmp.c (ffffffff8179747a)
Location: net/ipv4/igmp.c:1088
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81804bc7)
Location: net/ipv4/igmp.c:1086
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81835b97)
Location: net/ipv4/igmp.c:1101
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff818570eb)
Location: net/ipv4/igmp.c:1109
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff818d6f9b)
Location: net/ipv4/igmp.c:1137
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff8192d8cf)
Location: net/ipv4/igmp.c:1137
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff8195ce7f)
Location: net/ipv4/igmp.c:1148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff819c1b80)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff819f8720)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void igmpv3_add_delrec(struct in_device *in_dev, struct ip_mc_list *im, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae6f60)
Location: net/ipv4/igmp.c:1162
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
```
**Symbols:**

```
ffffffff81ae6f60-ffffffff81ae70c8: igmpv3_add_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void igmpv3_add_delrec(struct in_device *in_dev, struct ip_mc_list *im, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af3e30)
Location: net/ipv4/igmp.c:1162
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
```
**Symbols:**

```
ffffffff81af3e30-ffffffff81af3f98: igmpv3_add_delrec (STB_LOCAL)
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
In net/ipv4/igmp.c (ffffffff81ae0976)
Location: net/ipv4/igmp.c:1169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81b9ffa9)
Location: net/ipv4/igmp.c:1169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81d32414)
Location: net/ipv4/igmp.c:1172
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81efa3c4)
Location: net/ipv4/igmp.c:1172
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81f59e5f)
Location: net/ipv4/igmp.c:1173
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff8202037f)
Location: net/ipv4/igmp.c:1175
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffff800010cb121c)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (c0dbbc00)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (c000000000dc7f9c)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffe0008093c6)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff819984c0)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81951f80)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81a02d60)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
In net/ipv4/igmp.c (ffffffff81a0d290)
Location: net/ipv4/igmp.c:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__igmp_group_dropped
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
</ul>
