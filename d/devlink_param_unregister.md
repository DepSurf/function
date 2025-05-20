# Function: <code>devlink_param_unregister</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_param_unregister(struct devlink *devlink, const struct devlink_param *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b00410)
Location: net/core/devlink.c:10070
Inline: False
```
**Symbols:**

```
ffffffff81b00410-ffffffff81b0045b: devlink_param_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_param_unregister(struct devlink *devlink, const struct devlink_param *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c770a0)
Location: net/core/devlink.c:10903
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81c770a0-ffffffff81c77148: devlink_param_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_param_unregister(struct devlink *devlink, const struct devlink_param *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2f930)
Location: net/core/devlink.c:11686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:devlink_params_register
```
**Symbols:**

```
ffffffff81e2f930-ffffffff81e2f9d8: devlink_param_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_param_unregister(struct devlink *devlink, const struct devlink_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203b5b0)
Location: net/devlink/leftover.c:8180
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_params_unregister
  - net/devlink/leftover.c:devl_params_register
```
**Symbols:**

```
ffffffff8203b5b0-ffffffff8203b62c: devlink_param_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_param_unregister(struct devlink *devlink, const struct devlink_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/param.c (ffffffff8210e8d0)
Location: net/devlink/param.c:654
Inline: False
Direct callers:
  - net/devlink/param.c:devlink_params_unregister
  - net/devlink/param.c:devl_params_register
```
**Symbols:**

```
ffffffff8210e8d0-ffffffff8210e94c: devlink_param_unregister (STB_LOCAL)
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
