# Function: <code>get_links</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812845c0)
Location: fs/proc/proc_sysctl.c:1102
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812845c0-ffffffff812846b9: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1690)
Location: fs/proc/proc_sysctl.c:1108
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812b1690-ffffffff812b1789: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c6f30)
Location: fs/proc/proc_sysctl.c:1114
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812c6f30-ffffffff812c7029: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d4180)
Location: fs/proc/proc_sysctl.c:1178
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812d4180-ffffffff812d4272: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f89b0)
Location: fs/proc/proc_sysctl.c:1179
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812f89b0-ffffffff812f8aa2: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81326917)
Location: fs/proc/proc_sysctl.c:1181
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813259d0-ffffffff81325ac2: get_links.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133d767)
Location: fs/proc/proc_sysctl.c:1180
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8133caf0-ffffffff8133cbe2: get_links.part.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81364d80)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81364d80-ffffffff81364e74: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137d010)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8137d010-ffffffff8137d104: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c6ba0)
Location: fs/proc/proc_sysctl.c:1188
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813c6ba0-ffffffff813c6c94: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d8b70)
Location: fs/proc/proc_sysctl.c:1188
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813d8b70-ffffffff813d8c64: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813dfa40)
Location: fs/proc/proc_sysctl.c:1192
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813dfa40-ffffffff813dfb38: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814313d0)
Location: fs/proc/proc_sysctl.c:1192
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff814313d0-ffffffff814314c8: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ab400)
Location: fs/proc/proc_sysctl.c:1218
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff814ab400-ffffffff814ab521: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81541470)
Location: fs/proc/proc_sysctl.c:1217
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81541470-ffffffff81541591: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815799d0)
Location: fs/proc/proc_sysctl.c:1207
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815799d0-ffffffff81579af1: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table_header *header, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b2480)
Location: fs/proc/proc_sysctl.c:1199
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815b2480-ffffffff815b25d8: get_links (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff800010449a88)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffff800010449a88-ffff800010449ba0: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060e958)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
c060e958-c060ea80: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000560b80)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
c000000000560b80-c000000000560d3c: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002df420)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffe0002df420-ffffffe0002df4fe: get_links (STB_LOCAL)
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
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813755f0)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813755f0-ffffffff813756e4: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813660c0)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813660c0-ffffffff813661b4: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813730c0)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813730c0-ffffffff813731b4: get_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool get_links(struct ctl_dir *dir, struct ctl_table *table, struct ctl_table_root *link_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81386c10)
Location: fs/proc/proc_sysctl.c:1205
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81386c10-ffffffff81386d04: get_links (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<code>struct ctl_table_header *header</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ctl_table *table</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
