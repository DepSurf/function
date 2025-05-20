# Function: <code>devlink_get_from_attrs</code>

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
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946970)
Location: net/core/devlink.c:105
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81946970-ffffffff81946a27: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b770)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff8197b770-ffffffff8197b827: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a50e30)
Location: net/core/devlink.c:117
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81a50e30-ffffffff81a50ee7: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a57140)
Location: net/core/devlink.c:121
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81a57140-ffffffff81a571f7: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a39fa0)
Location: net/core/devlink.c:124
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81a39fa0-ffffffff81a3a057: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af23a0)
Location: net/core/devlink.c:123
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81af23a0-ffffffff81af24e4: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c87210)
Location: net/core/devlink.c:274
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81c87210-ffffffff81c87340: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e43280)
Location: net/core/devlink.c:356
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81e43280-ffffffff81e43376: devlink_get_from_attrs (STB_LOCAL)
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
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c230b0)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffff800010c230b0-ffff800010c23180: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a6f0)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
c0d3a6f0-c0d3a7a4: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15fc0)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
c000000000d15fc0-c000000000d163f0: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b998)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffe00079b998-ffffffe00079ba32: devlink_get_from_attrs (STB_LOCAL)
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
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b5e0)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff8191b5e0-ffffffff8191b697: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5390)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff818d5390-ffffffff818d5447: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c770)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff8196c770-ffffffff8196c827: devlink_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198ebf0)
Location: net/core/devlink.c:108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff8198ebf0-ffffffff8198eca7: devlink_get_from_attrs (STB_LOCAL)
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
