# Function: <code>__devlink_health_reporter_create</code>

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
struct devlink_health_reporter *__devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5a590)
Location: net/core/devlink.c:5888
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_create
  - net/core/devlink.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff81a5a590-ffffffff81a5a664: __devlink_health_reporter_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct devlink_health_reporter *__devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3c8c0)
Location: net/core/devlink.c:6091
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_create
  - net/core/devlink.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff81a3c8c0-ffffffff81a3c994: __devlink_health_reporter_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct devlink_health_reporter *__devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af3450)
Location: net/core/devlink.c:6704
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_create
  - net/core/devlink.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff81af3450-ffffffff81af3524: __devlink_health_reporter_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink_health_reporter *__devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c772b0)
Location: net/core/devlink.c:7196
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_create
  - net/core/devlink.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff81c772b0-ffffffff81c7738b: __devlink_health_reporter_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink_health_reporter *__devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2fd90)
Location: net/core/devlink.c:7751
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_health_reporter_create
  - net/core/devlink.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff81e2fd90-ffffffff81e2fe6b: __devlink_health_reporter_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_health_reporter *__devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82045d50)
Location: net/devlink/health.c:109
Inline: False
Direct callers:
  - net/devlink/health.c:devl_health_reporter_create
  - net/devlink/health.c:devl_port_health_reporter_create
```
**Symbols:**

```
ffffffff82045d50-ffffffff82045e19: __devlink_health_reporter_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_health_reporter *__devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82111a70)
Location: net/devlink/health.c:109
Inline: False
Direct callers:
  - net/devlink/health.c:devl_health_reporter_create
  - net/devlink/health.c:devl_port_health_reporter_create
```
**Symbols:**

```
ffffffff82111a70-ffffffff82111b44: __devlink_health_reporter_create (STB_LOCAL)
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
