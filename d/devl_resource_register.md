# Function: <code>devl_resource_register</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devl_resource_register(struct devlink *devlink, const char *resource_name, u64 resource_size, u64 resource_id, u64 parent_resource_id, const struct devlink_resource_size_params *size_params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e34050)
Location: net/core/devlink.c:11308
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_resource_register
```
**Symbols:**

```
ffffffff81e34050-ffffffff81e341e4: devl_resource_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devl_resource_register(struct devlink *devlink, const char *resource_name, u64 resource_size, u64 resource_id, u64 parent_resource_id, const struct devlink_resource_size_params *size_params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff820359e0)
Location: net/devlink/leftover.c:7865
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_resource_register
```
**Symbols:**

```
ffffffff820359e0-ffffffff82035b74: devl_resource_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devl_resource_register(struct devlink *devlink, const char *resource_name, u64 resource_size, u64 resource_id, u64 parent_resource_id, const struct devlink_resource_size_params *size_params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/resource.c (ffffffff8210d220)
Location: net/devlink/resource.c:334
Inline: False
Direct callers:
  - net/devlink/resource.c:devlink_resource_register
```
**Symbols:**

```
ffffffff8210d220-ffffffff8210d3e3: devl_resource_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
