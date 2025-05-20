# Function: <code>devlink_port_health_reporter_create</code>

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
struct devlink_health_reporter *devlink_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5a670)
Location: net/core/devlink.c:5922
Inline: False
```
**Symbols:**

```
ffffffff81a5a670-ffffffff81a5a740: devlink_port_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3cb20)
Location: net/core/devlink.c:6125
Inline: False
```
**Symbols:**

```
ffffffff81a3cb20-ffffffff81a3cbf0: devlink_port_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af3600)
Location: net/core/devlink.c:6738
Inline: False
```
**Symbols:**

```
ffffffff81af3600-ffffffff81af36d0: devlink_port_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c77470)
Location: net/core/devlink.c:7230
Inline: False
```
**Symbols:**

```
ffffffff81c77470-ffffffff81c7754c: devlink_port_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2ff70)
Location: net/core/devlink.c:7785
Inline: False
```
**Symbols:**

```
ffffffff81e2ff70-ffffffff81e3004c: devlink_port_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82046350)
Location: net/devlink/health.c:166
Inline: False
```
**Symbols:**

```
ffffffff82046350-ffffffff820463b0: devlink_port_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_port_health_reporter_create(struct devlink_port *port, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82111da0)
Location: net/devlink/health.c:165
Inline: False
```
**Symbols:**

```
ffffffff82111da0-ffffffff82111e00: devlink_port_health_reporter_create (STB_GLOBAL)
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
