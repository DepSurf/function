# Function: <code>add_mc_to_global_list</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8175bdb4)
Location: drivers/edac/edac_mc.c:628
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff817ce004)
Location: drivers/edac/edac_mc.c:628
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81816df4)
Location: drivers/edac/edac_mc.c:630
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff818426c5)
Location: drivers/edac/edac_mc.c:628
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81885525)
Location: drivers/edac/edac_mc.c:628
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff818b74c5)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_mc_to_global_list(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:590
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81987ed0-ffffffff81987f58: add_mc_to_global_list (STB_LOCAL)
ffffffff819892e1-ffffffff8198933e: add_mc_to_global_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int add_mc_to_global_list(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:594
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff8198be00-ffffffff8198be88: add_mc_to_global_list (STB_LOCAL)
ffffffff81c28716-ffffffff81c28773: add_mc_to_global_list.cold (STB_LOCAL)
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
In drivers/edac/edac_mc.c (ffffffff81970624)
Location: drivers/edac/edac_mc.c:594
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81a18f44)
Location: drivers/edac/edac_mc.c:597
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81b81d13)
Location: drivers/edac/edac_mc.c:522
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81d20467)
Location: drivers/edac/edac_mc.c:521
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81d89647)
Location: drivers/edac/edac_mc.c:521
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81e40d87)
Location: drivers/edac/edac_mc.c:522
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffff800010b0f5cc)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (c0bed8ac)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (c000000000c02bc0)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffe0006fc70a)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff8185d345)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff81824915)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff818ac975)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
In drivers/edac/edac_mc.c (ffffffff818c8bc5)
Location: drivers/edac/edac_mc.c:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
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
