# Function: <code>devlink_health_reporter_find_by_name</code>

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
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819468a0)
Location: net/core/devlink.c:4594
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffffffff819468a0-ffffffff819468f4: devlink_health_reporter_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b710)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffffffff8197b710-ffffffff8197b764: devlink_health_reporter_find_by_name (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a531d7)
Location: net/core/devlink.c:5166
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
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
In net/core/devlink.c (ffffffff81a59f5b)
Location: net/core/devlink.c:5870
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
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
In net/core/devlink.c (ffffffff81a3d0a7)
Location: net/core/devlink.c:6073
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
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
In net/core/devlink.c (ffffffff81af53a7)
Location: net/core/devlink.c:6686
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
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
In net/core/devlink.c (ffffffff81c79884)
Location: net/core/devlink.c:7178
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
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
In net/core/devlink.c (ffffffff81e3267f)
Location: net/core/devlink.c:7733
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
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
In net/devlink/health.c (ffffffff82046444)
Location: net/devlink/health.c:93
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_reporter_get_from_attrs
  - net/devlink/health.c:devl_health_reporter_create
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
In net/devlink/health.c (ffffffff82111e94)
Location: net/devlink/health.c:93
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_reporter_get_from_attrs
  - net/devlink/health.c:devl_health_reporter_create
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
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23030)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffff800010c23030-ffff800010c230ac: devlink_health_reporter_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a68c)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
c0d3a68c-c0d3a6f0: devlink_health_reporter_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15d80)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
c000000000d15d80-c000000000d15fc0: devlink_health_reporter_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b936)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffffffe00079b936-ffffffe00079b998: devlink_health_reporter_find_by_name (STB_LOCAL)
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
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b580)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffffffff8191b580-ffffffff8191b5d4: devlink_health_reporter_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5330)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffffffff818d5330-ffffffff818d5384: devlink_health_reporter_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c710)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffffffff8196c710-ffffffff8196c764: devlink_health_reporter_find_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_find_by_name(struct devlink *devlink, const char *reporter_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198eb90)
Location: net/core/devlink.c:4649
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_create
```
**Symbols:**

```
ffffffff8198eb90-ffffffff8198ebe4: devlink_health_reporter_find_by_name (STB_LOCAL)
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
