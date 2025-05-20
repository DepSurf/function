# Function: <code>devlink_info_version_put</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3910
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81949a80-ffffffff81949b6c: devlink_info_version_put.isra.0 (STB_LOCAL)
ffffffff81952168-ffffffff81952182: devlink_info_version_put.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff8197ef40)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff8197ef40-ffffffff8197f029: devlink_info_version_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a574e0)
Location: net/core/devlink.c:4391
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81a574e0-ffffffff81a575c9: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5f390)
Location: net/core/devlink.c:5080
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81a5f390-ffffffff81a5f479: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a40de0)
Location: net/core/devlink.c:5283
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81a40de0-ffffffff81a40ec7: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af7cf0)
Location: net/core/devlink.c:5893
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81af7cf0-ffffffff81af7dd7: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7cfc0)
Location: net/core/devlink.c:6388
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81c7cfc0-ffffffff81c7d0d2: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value, enum devlink_info_version_type version_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e36690)
Location: net/core/devlink.c:6902
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put_ext
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put_ext
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81e36690-ffffffff81e367c2: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value, enum devlink_info_version_type version_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82043cc0)
Location: net/devlink/dev.c:667
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_info_version_running_put_ext
  - net/devlink/dev.c:devlink_info_version_running_put
  - net/devlink/dev.c:devlink_info_version_stored_put_ext
  - net/devlink/dev.c:devlink_info_version_stored_put
  - net/devlink/dev.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff82043cc0-ffffffff82043df2: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value, enum devlink_info_version_type version_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82103490)
Location: net/devlink/dev.c:768
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_info_version_running_put_ext
  - net/devlink/dev.c:devlink_info_version_running_put
  - net/devlink/dev.c:devlink_info_version_stored_put_ext
  - net/devlink/dev.c:devlink_info_version_stored_put
  - net/devlink/dev.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff82103490-ffffffff821035c2: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c273c0)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffff800010c273c0-ffff800010c274e4: devlink_info_version_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_info_version_put(struct devlink_info_req *req, int attr, const char *version_name, const char *version_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3dd80)
Location: net/core/devlink.c:3964
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
c0d3dd80-c0d3de70: devlink_info_version_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c000000000d1bba0)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
c000000000d1bba0-c000000000d1bd50: devlink_info_version_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe00079f8dc)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffe00079f8dc-ffffffe00079f9b6: devlink_info_version_put.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff8191edb0)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff8191edb0-ffffffff8191ee99: devlink_info_version_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff818d8b60)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff818d8b60-ffffffff818d8c49: devlink_info_version_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff8196ff40)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff8196ff40-ffffffff81970029: devlink_info_version_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81992430)
Location: net/core/devlink.c:3964
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_info_version_running_put
  - net/core/devlink.c:devlink_info_version_stored_put
  - net/core/devlink.c:devlink_info_version_fixed_put
```
**Symbols:**

```
ffffffff81992430-ffffffff81992519: devlink_info_version_put.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum devlink_info_version_type version_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
