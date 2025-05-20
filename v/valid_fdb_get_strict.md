# Function: <code>valid_fdb_get_strict</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818cabac)
Location: net/core/rtnetlink.c:4024
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff81918235)
Location: net/core/rtnetlink.c:4092
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff8194a855)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff81a1b0aa)
Location: net/core/rtnetlink.c:4326
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff81a1b23a)
Location: net/core/rtnetlink.c:4418
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff81a02020)
Location: net/core/rtnetlink.c:4416
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
```
**Symbols:**

```
ffffffff81a02020-ffffffff81a02293: valid_fdb_get_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81ab4600)
Location: net/core/rtnetlink.c:4437
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
```
**Symbols:**

```
ffffffff81ab4600-ffffffff81ab4873: valid_fdb_get_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81c2e1af)
Location: net/core/rtnetlink.c:4558
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff81de13cf)
Location: net/core/rtnetlink.c:4609
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff81e52abf)
Location: net/core/rtnetlink.c:4698
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff81f11dcf)
Location: net/core/rtnetlink.c:4731
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffff800010bed7c4)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (c0d05d40)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (c000000000cd02b4)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffe0007704ce)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff818ea825)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff818a4665)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff8193b855)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
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
In net/core/rtnetlink.c (ffffffff8195d0d5)
Location: net/core/rtnetlink.c:4123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
```
</details>
</li>
</ul>

## Differences
