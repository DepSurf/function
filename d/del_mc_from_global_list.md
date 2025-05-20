# Function: <code>del_mc_from_global_list</code>

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
In drivers/edac/edac_mc.c (ffffffff8175c0f2)
Location: drivers/edac/edac_mc.c:667
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff817ce332)
Location: drivers/edac/edac_mc.c:667
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff8181707a)
Location: drivers/edac/edac_mc.c:669
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff8184291a)
Location: drivers/edac/edac_mc.c:667
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff81885726)
Location: drivers/edac/edac_mc.c:667
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff818b76c6)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int del_mc_from_global_list(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81988dd6)
Location: drivers/edac/edac_mc.c:629
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81988020-ffffffff81988087: del_mc_from_global_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int del_mc_from_global_list(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198c336)
Location: drivers/edac/edac_mc.c:633
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff8198bf50-ffffffff8198bfb7: del_mc_from_global_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int del_mc_from_global_list(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff819708d6)
Location: drivers/edac/edac_mc.c:633
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81970560-ffffffff819705c7: del_mc_from_global_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int del_mc_from_global_list(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81a191f6)
Location: drivers/edac/edac_mc.c:636
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81a18e80-ffffffff81a18ee7: del_mc_from_global_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int del_mc_from_global_list(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81b82145)
Location: drivers/edac/edac_mc.c:561
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
**Symbols:**

```
ffffffff81b81c40-ffffffff81b81caf: del_mc_from_global_list (STB_LOCAL)
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
In drivers/edac/edac_mc.c (ffffffff81d2097a)
Location: drivers/edac/edac_mc.c:560
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff81d89b7a)
Location: drivers/edac/edac_mc.c:560
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff81e412ca)
Location: drivers/edac/edac_mc.c:561
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffff800010b0f868)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (c0bedb38)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (c000000000c02f0c)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffe0006fc956)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff8185d546)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff81824b16)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff818acb76)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
In drivers/edac/edac_mc.c (ffffffff818c8dc6)
Location: drivers/edac/edac_mc.c:660
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
