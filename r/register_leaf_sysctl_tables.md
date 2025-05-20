# Function: <code>register_leaf_sysctl_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81285f30)
Location: fs/proc/proc_sysctl.c:1329
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff81285f30-ffffffff812860fc: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b30e0)
Location: fs/proc/proc_sysctl.c:1335
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff812b30e0-ffffffff812b32ae: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c8930)
Location: fs/proc/proc_sysctl.c:1341
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff812c8930-ffffffff812c8afe: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d5ca0)
Location: fs/proc/proc_sysctl.c:1405
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff812d5ca0-ffffffff812d5e5f: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812fa4e0)
Location: fs/proc/proc_sysctl.c:1406
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff812fa4e0-ffffffff812fa69f: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81327670)
Location: fs/proc/proc_sysctl.c:1408
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff81327670-ffffffff81327833: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133e800)
Location: fs/proc/proc_sysctl.c:1407
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff8133e800-ffffffff8133e9cd: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81366b30)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff81366b30-ffffffff81366cf8: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137edc0)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff8137edc0-ffffffff8137ef88: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c8e70)
Location: fs/proc/proc_sysctl.c:1415
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff813c8e70-ffffffff813c9038: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813dae60)
Location: fs/proc/proc_sysctl.c:1415
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff813dae60-ffffffff813db028: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e1d90)
Location: fs/proc/proc_sysctl.c:1419
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff813e1d90-ffffffff813e1f58: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814338a0)
Location: fs/proc/proc_sysctl.c:1419
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff814338a0-ffffffff81433a68: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ad7f0)
Location: fs/proc/proc_sysctl.c:1477
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff814ad7f0-ffffffff814ad9dc: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81543ce0)
Location: fs/proc/proc_sysctl.c:1476
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff81543ce0-ffffffff81543ecc: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044c380)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffff80001044c380-ffff80001044c544: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c0610dd0)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
c0610dd0-c0610fb4: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000563b10)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
c000000000563b10-c000000000563da0: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e14f8)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffe0002e14f8-ffffffe0002e1646: register_leaf_sysctl_tables (STB_LOCAL)
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
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813773a0)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff813773a0-ffffffff81377568: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81367e70)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff81367e70-ffffffff81368038: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81374e70)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff81374e70-ffffffff81375038: register_leaf_sysctl_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_leaf_sysctl_tables(const char *path, char *pos, struct ctl_table_header ***subheader, struct ctl_table_set *set, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81388840)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
**Symbols:**

```
ffffffff81388840-ffffffff81388a08: register_leaf_sysctl_tables (STB_LOCAL)
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
