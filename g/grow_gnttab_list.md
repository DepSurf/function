# Function: <code>grow_gnttab_list</code>

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
In drivers/xen/grant-table.c (ffffffff814c4fbc)
Location: drivers/xen/grant-table.c:566
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81515742)
Location: drivers/xen/grant-table.c:565
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81541bd2)
Location: drivers/xen/grant-table.c:565
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff815559d3)
Location: drivers/xen/grant-table.c:566
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff815b9638)
Location: drivers/xen/grant-table.c:657
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff815f2f99)
Location: drivers/xen/grant-table.c:657
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff8160d569)
Location: drivers/xen/grant-table.c:661
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81640fa5)
Location: drivers/xen/grant-table.c:661
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81663965)
Location: drivers/xen/grant-table.c:661
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int grow_gnttab_list(unsigned int more_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81711e00)
Location: drivers/xen/grant-table.c:660
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
```
**Symbols:**

```
ffffffff81711e00-ffffffff81711f83: grow_gnttab_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int grow_gnttab_list(unsigned int more_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172eb90)
Location: drivers/xen/grant-table.c:660
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
```
**Symbols:**

```
ffffffff8172eb90-ffffffff8172ed13: grow_gnttab_list (STB_LOCAL)
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
In drivers/xen/grant-table.c (ffffffff8171347f)
Location: drivers/xen/grant-table.c:660
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff817900cf)
Location: drivers/xen/grant-table.c:667
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff818c832e)
Location: drivers/xen/grant-table.c:736
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_expand
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
In drivers/xen/grant-table.c (ffffffff81a18d1e)
Location: drivers/xen/grant-table.c:736
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_expand
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
In drivers/xen/grant-table.c (ffffffff81a61d9e)
Location: drivers/xen/grant-table.c:754
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_expand
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
In drivers/xen/grant-table.c (ffffffff81ab45ce)
Location: drivers/xen/grant-table.c:752
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_expand
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
In drivers/xen/grant-table.c (ffff80001082dd08)
Location: drivers/xen/grant-table.c:661
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816297d5)
Location: drivers/xen/grant-table.c:661
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816577a5)
Location: drivers/xen/grant-table.c:661
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
In drivers/xen/grant-table.c (ffffffff81671da5)
Location: drivers/xen/grant-table.c:661
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
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
