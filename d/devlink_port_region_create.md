# Function: <code>devlink_port_region_create</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct devlink_region *devlink_port_region_create(struct devlink_port *port, const struct devlink_port_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60450)
Location: net/core/devlink.c:9275
Inline: False
```
**Symbols:**

```
ffffffff81a60450-ffffffff81a605ad: devlink_port_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct devlink_region *devlink_port_region_create(struct devlink_port *port, const struct devlink_port_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a424a0)
Location: net/core/devlink.c:9538
Inline: False
```
**Symbols:**

```
ffffffff81a424a0-ffffffff81a425fd: devlink_port_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct devlink_region *devlink_port_region_create(struct devlink_port *port, const struct devlink_port_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afab50)
Location: net/core/devlink.c:10480
Inline: False
```
**Symbols:**

```
ffffffff81afab50-ffffffff81afac9f: devlink_port_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink_region *devlink_port_region_create(struct devlink_port *port, const struct devlink_port_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7f690)
Location: net/core/devlink.c:11072
Inline: False
```
**Symbols:**

```
ffffffff81c7f690-ffffffff81c7f7eb: devlink_port_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink_region *devlink_port_region_create(struct devlink_port *port, const struct devlink_port_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e38730)
Location: net/core/devlink.c:11873
Inline: False
```
**Symbols:**

```
ffffffff81e38730-ffffffff81e388b7: devlink_port_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_region *devlink_port_region_create(struct devlink_port *port, const struct devlink_port_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82039890)
Location: net/devlink/leftover.c:8468
Inline: False
```
**Symbols:**

```
ffffffff82039890-ffffffff82039a06: devlink_port_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_region *devlink_port_region_create(struct devlink_port *port, const struct devlink_port_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff821104c0)
Location: net/devlink/region.c:1114
Inline: False
```
**Symbols:**

```
ffffffff821104c0-ffffffff82110665: devlink_port_region_create (STB_GLOBAL)
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
