# Function: <code>_opp_is_duplicate</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181e448)
Location: drivers/opp/core.c:1016
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff8184a249)
Location: drivers/opp/core.c:1162
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff8188d0bc)
Location: drivers/opp/core.c:1236
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff818bf2fc)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _opp_is_duplicate(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, struct list_head **head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1390
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
```
**Symbols:**

```
ffffffff8198e020-ffffffff8198e092: _opp_is_duplicate (STB_LOCAL)
ffffffff819912a2-ffffffff81991304: _opp_is_duplicate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _opp_is_duplicate(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, struct list_head **head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1474
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
```
**Symbols:**

```
ffffffff81991be0-ffffffff81991c52: _opp_is_duplicate (STB_LOCAL)
ffffffff81c28faa-ffffffff81c2900c: _opp_is_duplicate.cold (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff819797b8)
Location: drivers/opp/core.c:1631
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff81a227c8)
Location: drivers/opp/core.c:1641
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff81b8b877)
Location: drivers/opp/core.c:1785
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff81d2aee7)
Location: drivers/opp/core.c:1808
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff81d94168)
Location: drivers/opp/core.c:1816
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff81e4bc88)
Location: drivers/opp/core.c:1928
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffff800010b1a614)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (c0bf51b8)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (c000000000c0c37c)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffe000702d34)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff81863a1c)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff8182c6cc)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff818b47ac)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
In drivers/opp/core.c (ffffffff818d0a5c)
Location: drivers/opp/core.c:1285
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
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
