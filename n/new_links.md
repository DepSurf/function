# Function: <code>new_links</code>

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
In fs/proc/proc_sysctl.c (ffffffff8128561e)
Location: fs/proc/proc_sysctl.c:1059
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812b275e)
Location: fs/proc/proc_sysctl.c:1065
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812c7fae)
Location: fs/proc/proc_sysctl.c:1071
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812d5374)
Location: fs/proc/proc_sysctl.c:1135
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812f9bb4)
Location: fs/proc/proc_sysctl.c:1136
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff81326944)
Location: fs/proc/proc_sysctl.c:1138
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8133d794)
Location: fs/proc/proc_sysctl.c:1137
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff813662de)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8137e56e)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c7940)
Location: fs/proc/proc_sysctl.c:1145
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813c7940-ffffffff813c7af4: new_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d9930)
Location: fs/proc/proc_sysctl.c:1145
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813d9930-ffffffff813d9ae4: new_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813dff90)
Location: fs/proc/proc_sysctl.c:1149
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813dff90-ffffffff813e0144: new_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81431920)
Location: fs/proc/proc_sysctl.c:1149
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81431920-ffffffff81431ad4: new_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ac240)
Location: fs/proc/proc_sysctl.c:1173
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff814ac240-ffffffff814ac3ea: new_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81541ce0)
Location: fs/proc/proc_sysctl.c:1172
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81541ce0-ffffffff81541e9d: new_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815796b0)
Location: fs/proc/proc_sysctl.c:1162
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815796b0-ffffffff8157990a: new_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ctl_table_header *new_links(struct ctl_dir *dir, struct ctl_table_header *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b1ee0)
Location: fs/proc/proc_sysctl.c:1154
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815b1ee0-ffffffff815b2219: new_links (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffff80001044afb0)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (c0610370)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (c000000000562bd4)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffe0002e01b2)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff81376b4e)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8136761e)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8137461e)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8138802c)
Location: fs/proc/proc_sysctl.c:1162
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ctl_table_header *head</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ctl_table *table</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ctl_table_root *link_root</code>
</li>
</ul>
</details>
</li>
</ul>
