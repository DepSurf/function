# Function: <code>opp_debug_create_supplies</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff817d634a)
Location: drivers/opp/debugfs.c:38
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff8181f033)
Location: drivers/opp/debugfs.c:38
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff8184aed3)
Location: drivers/opp/debugfs.c:38
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff8188e03b)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff818c01cb)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void opp_debug_create_supplies(struct dev_pm_opp *opp, struct opp_table *opp_table, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81991d00)
Location: drivers/opp/debugfs.c:76
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81991d00-ffffffff81991e1f: opp_debug_create_supplies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void opp_debug_create_supplies(struct dev_pm_opp *opp, struct opp_table *opp_table, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81994f90)
Location: drivers/opp/debugfs.c:76
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81994f90-ffffffff819950af: opp_debug_create_supplies (STB_LOCAL)
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
In drivers/opp/debugfs.c (ffffffff8197a183)
Location: drivers/opp/debugfs.c:76
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81a23193)
Location: drivers/opp/debugfs.c:76
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81b8c39d)
Location: drivers/opp/debugfs.c:77
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81d2bd0c)
Location: drivers/opp/debugfs.c:95
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81d94f9a)
Location: drivers/opp/debugfs.c:95
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81e4caaa)
Location: drivers/opp/debugfs.c:95
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffff800010b1cacc)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (c0bf7274)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (c000000000c0f40c)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffe000704a7e)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff818648eb)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff8182d59b)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff818b567b)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff818d192b)
Location: drivers/opp/debugfs.c:35
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
