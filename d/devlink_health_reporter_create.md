# Function: <code>devlink_health_reporter_create</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4616
Inline: False
```
**Symbols:**

```
ffffffff81952085-ffffffff819520b9: devlink_health_reporter_create.cold (STB_LOCAL)
ffffffff81947990-ffffffff81947aa8: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197ca80)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
ffffffff8197ca80-ffffffff8197cbb7: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a542b0)
Location: net/core/devlink.c:5187
Inline: False
```
**Symbols:**

```
ffffffff81a542b0-ffffffff81a543fb: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5a740)
Location: net/core/devlink.c:5957
Inline: False
```
**Symbols:**

```
ffffffff81a5a740-ffffffff81a5a7ff: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3ca60)
Location: net/core/devlink.c:6160
Inline: False
```
**Symbols:**

```
ffffffff81a3ca60-ffffffff81a3cb1f: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af3530)
Location: net/core/devlink.c:6773
Inline: False
```
**Symbols:**

```
ffffffff81af3530-ffffffff81af35f5: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c77390)
Location: net/core/devlink.c:7265
Inline: False
```
**Symbols:**

```
ffffffff81c77390-ffffffff81c77461: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2fe80)
Location: net/core/devlink.c:7820
Inline: False
```
**Symbols:**

```
ffffffff81e2fe80-ffffffff81e2ff51: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff820461f0)
Location: net/devlink/health.c:212
Inline: False
```
**Symbols:**

```
ffffffff820461f0-ffffffff82046245: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82111c40)
Location: net/devlink/health.c:211
Inline: False
```
**Symbols:**

```
ffffffff82111c40-ffffffff82111c95: devlink_health_reporter_create (STB_GLOBAL)
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
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c246b0)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
ffff800010c246b0-ffff800010c247c4: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3bc34)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
c0d3bc34-c0d3bd6c: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d193e0)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
c000000000d193e0-c000000000d19650: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079cb5c)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
ffffffe00079cb5c-ffffffe00079cc54: devlink_health_reporter_create (STB_GLOBAL)
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
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191c8f0)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
ffffffff8191c8f0-ffffffff8191ca27: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d66a0)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
ffffffff818d66a0-ffffffff818d67d7: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196da80)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
ffffffff8196da80-ffffffff8196dbb7: devlink_health_reporter_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_health_reporter *devlink_health_reporter_create(struct devlink *devlink, const struct devlink_health_reporter_ops *ops, u64 graceful_period, bool auto_recover, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198fed0)
Location: net/core/devlink.c:4671
Inline: False
```
**Symbols:**

```
ffffffff8198fed0-ffffffff81990007: devlink_health_reporter_create (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool auto_recover</code>
</li>
<li>
<b>Param reordered. </b>
<code>devlink, ops, graceful_period, auto_recover, priv</code> ➡️ <code>devlink, ops, graceful_period, priv</code>
</li>
</ul>
</details>
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
