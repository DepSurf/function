# Function: <code>devlink_region_get_by_name</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946c10)
Location: net/core/devlink.c:351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffffffff81946c10-ffffffff81946c6a: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b830)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffffffff8197b830-ffffffff8197b88a: devlink_region_get_by_name (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a58515)
Location: net/core/devlink.c:362
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
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
In net/core/devlink.c (ffffffff81a60355)
Location: net/core/devlink.c:370
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
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
In net/core/devlink.c (ffffffff81a423a5)
Location: net/core/devlink.c:373
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
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
In net/core/devlink.c (ffffffff81afaa65)
Location: net/core/devlink.c:448
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
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
In net/core/devlink.c (ffffffff81c7f595)
Location: net/core/devlink.c:651
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
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
In net/core/devlink.c (ffffffff81e385a2)
Location: net/core/devlink.c:805
Inline: True
Inline callers:
  - net/core/devlink.c:devl_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
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
In net/devlink/leftover.c (ffffffff82039707)
Location: net/devlink/leftover.c:558
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_region_create
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_del
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
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
In net/devlink/region.c (ffffffff82110307)
Location: net/devlink/region.c:35
Inline: True
Inline callers:
  - net/devlink/region.c:devl_region_create
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_del_doit
  - net/devlink/region.c:devlink_nl_region_get_doit
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
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23180)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffff800010c23180-ffff800010c23200: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a7a4)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
c0d3a7a4-c0d3a80c: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d163f0)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
c000000000d163f0-c000000000d16630: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079ba32)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffffffe00079ba32-ffffffe00079ba9a: devlink_region_get_by_name (STB_LOCAL)
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
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b6a0)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffffffff8191b6a0-ffffffff8191b6fa: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5450)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffffffff818d5450-ffffffff818d54aa: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c830)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffffffff8196c830-ffffffff8196c88a: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_region *devlink_region_get_by_name(struct devlink *devlink, const char *region_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198ecb0)
Location: net/core/devlink.c:354
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
```
**Symbols:**

```
ffffffff8198ecb0-ffffffff8198ed0a: devlink_region_get_by_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
