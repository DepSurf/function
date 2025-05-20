# Function: <code>devlink_dpipe_table_register</code>

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
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6027
Inline: False
```
**Symbols:**

```
ffffffff8195206d-ffffffff81952085: devlink_dpipe_table_register.cold (STB_LOCAL)
ffffffff81947470-ffffffff81947539: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197c5c0)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
ffffffff8197c5c0-ffffffff8197c68e: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a54400)
Location: net/core/devlink.c:7661
Inline: False
```
**Symbols:**

```
ffffffff81a54400-ffffffff81a544fa: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b360)
Location: net/core/devlink.c:8549
Inline: False
```
**Symbols:**

```
ffffffff81a5b360-ffffffff81a5b45a: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3da40)
Location: net/core/devlink.c:8808
Inline: False
```
**Symbols:**

```
ffffffff81a3da40-ffffffff81a3db3a: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af3ea0)
Location: net/core/devlink.c:9653
Inline: False
```
**Symbols:**

```
ffffffff81af3ea0-ffffffff81af3f9a: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c78140)
Location: net/core/devlink.c:10517
Inline: False
```
**Symbols:**

```
ffffffff81c78140-ffffffff81c78247: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c241a0)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
ffff800010c241a0-ffff800010c2427c: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3b688)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
c0d3b688-c0d3b774: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1b0c0)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
c000000000d1b0c0-c000000000d1b1fc: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079c782)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
ffffffe00079c782-ffffffe00079c84c: devlink_dpipe_table_register (STB_GLOBAL)
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
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191c430)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
ffffffff8191c430-ffffffff8191c4fe: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d61e0)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
ffffffff818d61e0-ffffffff818d62ae: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196d5c0)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
ffffffff8196d5c0-ffffffff8196d68e: devlink_dpipe_table_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_dpipe_table_register(struct devlink *devlink, const char *table_name, struct devlink_dpipe_table_ops *table_ops, void *priv, bool counter_control_extern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198fa10)
Location: net/core/devlink.c:6724
Inline: False
```
**Symbols:**

```
ffffffff8198fa10-ffffffff8198fade: devlink_dpipe_table_register (STB_GLOBAL)
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
