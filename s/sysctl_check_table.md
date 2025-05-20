# Function: <code>sysctl_check_table</code>

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
In fs/proc/proc_sysctl.c (ffffffff81285a64)
Location: fs/proc/proc_sysctl.c:1029
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (ffffffff812b2bb0)
Location: fs/proc/proc_sysctl.c:1035
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (ffffffff812c8400)
Location: fs/proc/proc_sysctl.c:1041
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (ffffffff812d5791)
Location: fs/proc/proc_sysctl.c:1101
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (ffffffff812f9fd1)
Location: fs/proc/proc_sysctl.c:1102
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1104
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1103
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1111
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff813c6690-ffffffff813c67a5: sysctl_check_table (STB_LOCAL)
ffffffff813c9414-ffffffff813c94f7: sysctl_check_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1111
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff813d8630-ffffffff813d8745: sysctl_check_table (STB_LOCAL)
ffffffff81bebd9f-ffffffff81bebe82: sysctl_check_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1114
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff813df4c0-ffffffff813df619: sysctl_check_table (STB_LOCAL)
ffffffff81bdddae-ffffffff81bddebf: sysctl_check_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1114
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff81430e70-ffffffff81430fc9: sysctl_check_table (STB_LOCAL)
ffffffff81cc81c5-ffffffff81cc82d6: sysctl_check_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1137
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff814aabe0-ffffffff814aad45: sysctl_check_table (STB_LOCAL)
ffffffff81e7adb2-ffffffff81e7aec3: sysctl_check_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81540980)
Location: fs/proc/proc_sysctl.c:1135
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff81540980-ffffffff81540c26: sysctl_check_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81578d40)
Location: fs/proc/proc_sysctl.c:1128
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff81578d40-ffffffff81578fd5: sysctl_check_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysctl_check_table(const char *path, struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b1510)
Location: fs/proc/proc_sysctl.c:1120
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff815b1510-ffffffff815b17a3: sysctl_check_table (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (ffffffe0002e0eee)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1128
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_table
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
