# Function: <code>devl_port_health_reporter_create</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_health_reporter *devl_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82046260)
Location: net/devlink/health.c:142
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff82046260-ffffffff8204633a: devl_port_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_health_reporter *devl_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82111cb0)
Location: net/devlink/health.c:141
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff82111cb0-ffffffff82111d8a: devl_port_health_reporter_create (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
