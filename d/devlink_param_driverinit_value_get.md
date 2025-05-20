# Function: <code>devlink_param_driverinit_value_get</code>

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
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946330)
Location: net/core/devlink.c:6538
Inline: False
```
**Symbols:**

```
ffffffff81946330-ffffffff81946357: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b2d0)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
ffffffff8197b2d0-ffffffff8197b2fe: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a52d10)
Location: net/core/devlink.c:8180
Inline: False
```
**Symbols:**

```
ffffffff81a52d10-ffffffff81a52d3e: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59400)
Location: net/core/devlink.c:9068
Inline: False
```
**Symbols:**

```
ffffffff81a59400-ffffffff81a5942f: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3c370)
Location: net/core/devlink.c:9331
Inline: False
```
**Symbols:**

```
ffffffff81a3c370-ffffffff81a3c39f: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af2da0)
Location: net/core/devlink.c:10273
Inline: False
```
**Symbols:**

```
ffffffff81af2da0-ffffffff81af2dcf: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:10929
Inline: False
```
**Symbols:**

```
ffffffff81f04d32-ffffffff81f04d5f: devlink_param_driverinit_value_get.cold (STB_LOCAL)
ffffffff81c73c30-ffffffff81c73de3: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:11712
Inline: False
```
**Symbols:**

```
ffffffff820acf44-ffffffff820acf59: devlink_param_driverinit_value_get.cold (STB_LOCAL)
ffffffff81e31290-ffffffff81e3145b: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
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
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c22b18)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
ffff800010c22b18-ffff800010c22b84: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d39e68)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
c0d39e68-c0d39eac: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15350)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
c000000000d15350-c000000000d15398: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b478)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
ffffffe00079b478-ffffffe00079b4d0: devlink_param_driverinit_value_get (STB_GLOBAL)
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
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b140)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
ffffffff8191b140-ffffffff8191b16e: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d4ef0)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
ffffffff818d4ef0-ffffffff818d4f1e: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c2d0)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
ffffffff8196c2d0-ffffffff8196c2fe: devlink_param_driverinit_value_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_param_driverinit_value_get(struct devlink *devlink, u32 param_id, union devlink_param_value *init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198e750)
Location: net/core/devlink.c:7235
Inline: False
```
**Symbols:**

```
ffffffff8198e750-ffffffff8198e77e: devlink_param_driverinit_value_get (STB_GLOBAL)
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
