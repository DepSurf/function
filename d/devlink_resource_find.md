# Function: <code>devlink_resource_find</code>

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
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819460c0)
Location: net/core/devlink.c:2392
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffffffff819460c0-ffffffff81946138: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b0a0)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffffffff8197b0a0-ffffffff8197b118: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a553bb)
Location: net/core/devlink.c:2426
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
ffffffff81a54f00-ffffffff81a552d2: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5c75b)
Location: net/core/devlink.c:2758
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
ffffffff81a5c2a0-ffffffff81a5c672: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4086b)
Location: net/core/devlink.c:2961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
ffffffff81a403c0-ffffffff81a40783: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af782b)
Location: net/core/devlink.c:3523
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
ffffffff81af72d0-ffffffff81af7693: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7b17b)
Location: net/core/devlink.c:4038
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
ffffffff81c7ab40-ffffffff81c7afe0: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e33cbb)
Location: net/core/devlink.c:4303
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devl_resource_size_get
  - net/core/devlink.c:devl_resource_register
  - net/core/devlink.c:devl_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devl_resource_size_get
  - net/core/devlink.c:devl_resource_register
  - net/core/devlink.c:devl_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
ffffffff81e334e0-ffffffff81e33980: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203564f)
Location: net/devlink/leftover.c:3521
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_resource_occ_get_unregister
  - net/devlink/leftover.c:devlink_resource_occ_get_register
  - net/devlink/leftover.c:devl_resource_size_get
  - net/devlink/leftover.c:devl_resource_register
  - net/devlink/leftover.c:devl_resource_register
  - net/devlink/leftover.c:devlink_nl_cmd_resource_set
Direct callers:
  - net/devlink/leftover.c:devlink_resource_occ_get_unregister
  - net/devlink/leftover.c:devlink_resource_occ_get_register
  - net/devlink/leftover.c:devl_resource_size_get
  - net/devlink/leftover.c:devl_resource_register
  - net/devlink/leftover.c:devl_resource_register
  - net/devlink/leftover.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
ffffffff82034ea0-ffffffff82035330: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/resource.c (ffffffff8210d18f)
Location: net/devlink/resource.c:39
Inline: True
Inline callers:
  - net/devlink/resource.c:devlink_resource_occ_get_unregister
  - net/devlink/resource.c:devlink_resource_occ_get_register
  - net/devlink/resource.c:devl_resource_size_get
  - net/devlink/resource.c:devl_resource_register
  - net/devlink/resource.c:devl_resource_register
  - net/devlink/resource.c:devlink_nl_resource_set_doit
Direct callers:
  - net/devlink/resource.c:devlink_resource_occ_get_unregister
  - net/devlink/resource.c:devlink_resource_occ_get_register
  - net/devlink/resource.c:devl_resource_size_get
  - net/devlink/resource.c:devl_resource_register
  - net/devlink/resource.c:devl_resource_register
  - net/devlink/resource.c:devlink_nl_resource_set_doit
```
**Symbols:**

```
ffffffff8210c9e0-ffffffff8210ce70: devlink_resource_find (STB_LOCAL)
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
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c22810)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffff800010c22810-ffff800010c228b0: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d39b74)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
c0d39b74-c0d39c00: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d14f70)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
c000000000d14f70-c000000000d15088: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b208)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffffffe00079b208-ffffffe00079b284: devlink_resource_find (STB_LOCAL)
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
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191af10)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffffffff8191af10-ffffffff8191af88: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d4cc0)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffffffff818d4cc0-ffffffff818d4d38: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c0a0)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffffffff8196c0a0-ffffffff8196c118: devlink_resource_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_resource *devlink_resource_find(struct devlink *devlink, struct devlink_resource *resource, u64 resource_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198e520)
Location: net/core/devlink.c:2394
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resource_size_get
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_resource_find
```
**Symbols:**

```
ffffffff8198e520-ffffffff8198e598: devlink_resource_find (STB_LOCAL)
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
