# Function: <code>devlink_resources_validate</code>

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
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946140)
Location: net/core/devlink.c:2653
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffffffff81946140-ffffffff819461b0: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b120)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffffffff8197b120-ffffffff8197b190: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5daf7)
Location: net/core/devlink.c:2687
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a53f80-ffffffff81a542ad: devlink_resources_validate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ac60)
Location: net/core/devlink.c:3019
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a5ac60-ffffffff81a5af8d: devlink_resources_validate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a86d)
Location: net/core/devlink.c:3222
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a3ebc0-ffffffff81a3eeed: devlink_resources_validate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3784
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81af2bc0-ffffffff81af2c39: devlink_resources_validate.isra.0 (STB_LOCAL)
ffffffff81d383e4-ffffffff81d383f9: devlink_resources_validate.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4299
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81c76b70-ffffffff81c76bf9: devlink_resources_validate.isra.0 (STB_LOCAL)
ffffffff81f04de3-ffffffff81f04df8: devlink_resources_validate.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4565
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81e2f3a0-ffffffff81e2f429: devlink_resources_validate.isra.0 (STB_LOCAL)
ffffffff820acdcc-ffffffff820acde1: devlink_resources_validate.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:3782
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_resources_validate
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff8213661a-ffffffff8213662f: devlink_resources_validate.cold (STB_LOCAL)
ffffffff82041450-ffffffff820414e9: devlink_resources_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/resource.c (0)
Location: net/devlink/resource.c:298
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/resource.c:devlink_resources_validate
```
**Symbols:**

```
ffffffff822181c6-ffffffff822181db: devlink_resources_validate.cold (STB_LOCAL)
ffffffff8210d7e0-ffffffff8210d879: devlink_resources_validate (STB_GLOBAL)
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
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c228b0)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffff800010c228b0-ffff800010c2294c: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d39c00)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
c0d39c00-c0d39c80: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15090)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
c000000000d15090-c000000000d15198: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b284)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffffffe00079b284-ffffffe00079b300: devlink_resources_validate (STB_LOCAL)
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
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191af90)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffffffff8191af90-ffffffff8191b000: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d4d40)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffffffff818d4d40-ffffffff818d4db0: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c120)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffffffff8196c120-ffffffff8196c190: devlink_resources_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_resources_validate(struct devlink *devlink, struct devlink_resource *resource, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198e5a0)
Location: net/core/devlink.c:2655
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_resources_validate
```
**Symbols:**

```
ffffffff8198e5a0-ffffffff8198e610: devlink_resources_validate (STB_LOCAL)
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
