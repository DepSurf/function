# Function: <code>_opp_kref_release_unlocked</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void _opp_kref_release_unlocked(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848730)
Location: drivers/opp/core.c:1005
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81848730-ffffffff81848748: _opp_kref_release_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _opp_kref_release_unlocked(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188b7a0)
Location: drivers/opp/core.c:1079
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff8188b7a0-ffffffff8188b7b8: _opp_kref_release_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _opp_kref_release_unlocked(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bd870)
Location: drivers/opp/core.c:1128
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff818bd870-ffffffff818bd888: _opp_kref_release_unlocked (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff8198f1d8)
Location: drivers/opp/core.c:1191
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
In drivers/opp/core.c (ffff800010b18db8)
Location: drivers/opp/core.c:1128
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
In drivers/opp/core.c (c0bf3c34)
Location: drivers/opp/core.c:1128
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
In drivers/opp/core.c (c000000000c0a748)
Location: drivers/opp/core.c:1128
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
In drivers/opp/core.c (ffffffe0007018a4)
Location: drivers/opp/core.c:1128
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
<summary>In <code>aws</code>: ✅</summary>

```c
void _opp_kref_release_unlocked(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81861f90)
Location: drivers/opp/core.c:1128
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81861f90-ffffffff81861fa8: _opp_kref_release_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _opp_kref_release_unlocked(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182ac40)
Location: drivers/opp/core.c:1128
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff8182ac40-ffffffff8182ac58: _opp_kref_release_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _opp_kref_release_unlocked(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2d20)
Location: drivers/opp/core.c:1128
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff818b2d20-ffffffff818b2d38: _opp_kref_release_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _opp_kref_release_unlocked(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cefd0)
Location: drivers/opp/core.c:1128
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff818cefd0-ffffffff818cefe8: _opp_kref_release_unlocked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
