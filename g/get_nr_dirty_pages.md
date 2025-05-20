# Function: <code>get_nr_dirty_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int get_nr_dirty_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81235fc0)
Location: fs/fs-writeback.c:1761
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wakeup_flusher_threads
```
**Symbols:**

```
ffffffff81235fc0-ffffffff81235ff7: get_nr_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_nr_dirty_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8125f930)
Location: fs/fs-writeback.c:1809
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff8125f930-ffffffff8125f966: get_nr_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_nr_dirty_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81272e50)
Location: fs/fs-writeback.c:1807
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff81272e50-ffffffff81272e86: get_nr_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int get_nr_dirty_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81280230)
Location: fs/fs-writeback.c:1821
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff81280230-ffffffff81280266: get_nr_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int get_nr_dirty_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a2d60)
Location: fs/fs-writeback.c:940
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff812a2d60-ffffffff812a2d96: get_nr_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_nr_dirty_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c97e0)
Location: fs/fs-writeback.c:941
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff812c97e0-ffffffff812c9816: get_nr_dirty_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int get_nr_dirty_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812dea10)
Location: fs/fs-writeback.c:967
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff812dea10-ffffffff812dea46: get_nr_dirty_pages (STB_LOCAL)
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
In fs/fs-writeback.c (ffffffff812ff7d6)
Location: fs/fs-writeback.c:982
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff813146e6)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff8134e1c6)
Location: fs/fs-writeback.c:1071
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_check_start_all
  - fs/fs-writeback.c:wb_check_old_data_flush
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
In fs/fs-writeback.c (ffffffff8135b076)
Location: fs/fs-writeback.c:1071
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_check_start_all
  - fs/fs-writeback.c:wb_check_old_data_flush
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
In fs/fs-writeback.c (ffffffff81361c76)
Location: fs/fs-writeback.c:1077
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff813b02d6)
Location: fs/fs-writeback.c:1216
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff81434f06)
Location: fs/fs-writeback.c:1182
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff814c2f36)
Location: fs/fs-writeback.c:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff814f8316)
Location: fs/fs-writeback.c:1190
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff8152ca96)
Location: fs/fs-writeback.c:1207
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffff8000103ca578)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (c05a6b84)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (c0000000004cbed8)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffe00028878a)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff8130ccc6)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff812fd8e6)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff8130aab6)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff8131c1e6)
Location: fs/fs-writeback.c:1070
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
