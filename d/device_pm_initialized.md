# Function: <code>device_pm_initialized</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/power/power.h:147
Inline: True
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
In drivers/base/core.c (0)
Location: drivers/base/power/power.h:147
Inline: True
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
In drivers/base/core.c (0)
Location: drivers/base/power/power.h:148
Inline: True
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
In drivers/base/core.c (ffffffff8167ee25)
Location: drivers/base/power/power.h:114
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
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
In drivers/base/core.c (ffffffff8169f265)
Location: drivers/base/power/power.h:114
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
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
In drivers/base/core.c (ffffffff816d78a5)
Location: drivers/base/power/power.h:115
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fbb02)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff8170f484)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b5341)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff817cb076)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c9a31)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff817dfb06)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ad22a)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff817c3ee6)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8183651f)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff8184e2b6)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8197851f)
Location: drivers/base/power/power.h:121
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff81993e07)
Location: drivers/base/power/power.h:121
Inline: True
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
In drivers/base/core.c (ffffffff81ae4de2)
Location: drivers/base/power/power.h:121
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff81b04767)
Location: drivers/base/power/power.h:121
Inline: True
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
In drivers/base/core.c (ffffffff81b33105)
Location: drivers/base/power/power.h:122
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff81b51fe7)
Location: drivers/base/power/power.h:122
Inline: True
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
In drivers/base/core.c (ffffffff81b8aa15)
Location: drivers/base/power/power.h:122
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff81baa5d7)
Location: drivers/base/power/power.h:122
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e6458)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffff8000108ffb0c)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d4a80)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (c09e9e48)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097c150)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (c00000000099ce78)
Location: drivers/base/power/power.h:118
Inline: True
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
In drivers/base/core.c (ffffffe00057aeba)
Location: drivers/base/power/power.h:142
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c12f2)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff816d51c4)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c5a2)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff816afe74)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef7c2)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff81703144)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170a002)
Location: drivers/base/power/power.h:118
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_reorder_to_tail
```
```
In drivers/base/power/main.c (ffffffff8171d9c4)
Location: drivers/base/power/power.h:118
Inline: True
```
</details>
</li>
</ul>

## Differences
