# Function: <code>del_from_avail_list</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812263d0)
Location: mm/swapfile.c:603
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapoff
```
**Symbols:**

```
ffffffff812263d0-ffffffff81226402: del_from_avail_list (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8124c9c0)
Location: mm/swapfile.c:603
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff81260eea)
Location: mm/swapfile.c:631
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff8127be3d)
Location: mm/swapfile.c:666
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff8128b91d)
Location: mm/swapfile.c:666
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff812be80d)
Location: mm/swapfile.c:660
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff812ca3ed)
Location: mm/swapfile.c:673
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff812d0f1a)
Location: mm/swapfile.c:672
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff8131660b)
Location: mm/swapfile.c:680
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff813817c2)
Location: mm/swapfile.c:682
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff813fff4c)
Location: mm/swapfile.c:686
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff81432e03)
Location: mm/swapfile.c:688
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff8146c223)
Location: mm/swapfile.c:690
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffff800010326cd0)
Location: mm/swapfile.c:666
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:scan_swap_map_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053aecc)
Location: mm/swapfile.c:666
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
c053aecc-c053af1c: del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f84b0)
Location: mm/swapfile.c:666
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
c0000000003f84b0-c0000000003f856c: del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000223bf0)
Location: mm/swapfile.c:666
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffe000223bf0-ffffffe000223c78: del_from_avail_list (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81283efd)
Location: mm/swapfile.c:666
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff81275d8d)
Location: mm/swapfile.c:666
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff81281d0d)
Location: mm/swapfile.c:666
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
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
In mm/swapfile.c (ffffffff81291a22)
Location: mm/swapfile.c:666
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
