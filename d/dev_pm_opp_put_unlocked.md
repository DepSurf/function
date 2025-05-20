# Function: <code>dev_pm_opp_put_unlocked</code>

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
In drivers/opp/core.c (ffffffff81848fe4)
Location: drivers/opp/core.c:1034
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffff8188becd)
Location: drivers/opp/core.c:1108
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffff818bdfad)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffff8198f154)
Location: drivers/opp/core.c:1220
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all_static
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/opp/core.c (ffff800010b18da4)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (c0bf3c20)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (c000000000c0a720)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffe00070187e)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffff818626cd)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffff8182b37d)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffff818b345d)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
In drivers/opp/core.c (ffffffff818cf70d)
Location: drivers/opp/core.c:1157
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
</details>
</li>
</ul>

## Differences
