# Function: <code>devlink_health_reporter_get_from_attrs</code>

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
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946900)
Location: net/core/devlink.c:4801
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81946900-ffffffff81946962: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197ba10)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff8197ba10-ffffffff8197ba72: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a531a0)
Location: net/core/devlink.c:5465
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81a531a0-ffffffff81a53256: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59e40)
Location: net/core/devlink.c:6260
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81a59e40-ffffffff81a59fef: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3cf90)
Location: net/core/devlink.c:6463
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81a3cf90-ffffffff81a3d13b: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af5290)
Location: net/core/devlink.c:7075
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81af5290-ffffffff81af543b: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c79770)
Location: net/core/devlink.c:7568
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81c79770-ffffffff81c79915: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e32580)
Location: net/core/devlink.c:8125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff81e32580-ffffffff81e32715: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff820463c0)
Location: net/devlink/health.c:333
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_test_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_set_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff820463c0-ffffffff82046470: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82111e10)
Location: net/devlink/health.c:331
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_health_reporter_test_doit
  - net/devlink/health.c:devlink_nl_health_reporter_dump_clear_doit
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_recover_doit
  - net/devlink/health.c:devlink_nl_health_reporter_set_doit
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
```
**Symbols:**

```
ffffffff82111e10-ffffffff82111ec0: devlink_health_reporter_get_from_attrs (STB_LOCAL)
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
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23a08)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffff800010c23a08-ffff800010c23a74: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3af4c)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
c0d3af4c-c0d3afa8: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d16bf0)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
c000000000d16bf0-c000000000d16c8c: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079bc1c)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffe00079bc1c-ffffffe00079bc82: devlink_health_reporter_get_from_attrs (STB_LOCAL)
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
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b880)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff8191b880-ffffffff8191b8e2: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5630)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff818d5630-ffffffff818d5692: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196ca10)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff8196ca10-ffffffff8196ca72: devlink_health_reporter_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198ee60)
Location: net/core/devlink.c:4857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
**Symbols:**

```
ffffffff8198ee60-ffffffff8198eec2: devlink_health_reporter_get_from_attrs (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
