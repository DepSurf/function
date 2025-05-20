# Function: <code>netif_set_gso_max_segs</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0ad69)
Location: net/core/dev.h:98
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
```
```
In net/core/rtnetlink.c (ffffffff81c2b042)
Location: net/core/dev.h:98
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbac89)
Location: net/core/dev.h:105
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
```
```
In net/core/rtnetlink.c (ffffffff81dde994)
Location: net/core/dev.h:105
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e30810)
Location: net/core/dev.h:108
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
```
```
In net/core/rtnetlink.c (ffffffff81e4fa05)
Location: net/core/dev.h:108
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eef1a1)
Location: net/core/dev.h:113
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
```
```
In net/core/rtnetlink.c (ffffffff81f0ea3e)
Location: net/core/dev.h:113
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
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
