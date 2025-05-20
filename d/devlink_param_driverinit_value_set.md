# Function: <code>devlink_param_driverinit_value_set</code>

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
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81951000)
Location: net/core/devlink.c:6561
Inline: False
```
**Symbols:**

```
ffffffff81951000-ffffffff8195102a: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819876d0)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
ffffffff819876d0-ffffffff819876fa: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d870)
Location: net/core/devlink.c:8203
Inline: False
```
**Symbols:**

```
ffffffff81a5d870-ffffffff81a5d89a: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a64c60)
Location: net/core/devlink.c:9091
Inline: False
```
**Symbols:**

```
ffffffff81a64c60-ffffffff81a64c8a: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a48c80)
Location: net/core/devlink.c:9354
Inline: False
```
**Symbols:**

```
ffffffff81a48c80-ffffffff81a48caa: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81affec0)
Location: net/core/devlink.c:10296
Inline: False
```
**Symbols:**

```
ffffffff81affec0-ffffffff81affeea: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:10967
Inline: False
```
**Symbols:**

```
ffffffff81f04d1a-ffffffff81f04d32: devlink_param_driverinit_value_set.cold (STB_LOCAL)
ffffffff81c73240-ffffffff81c733cd: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e310d0)
Location: net/core/devlink.c:11750
Inline: False
```
**Symbols:**

```
ffffffff81e310d0-ffffffff81e31275: devlink_param_driverinit_value_set (STB_GLOBAL)
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
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2fb88)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
ffff800010c2fb88-ffff800010c2fbe8: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d46b30)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
c0d46b30-c0d46b98: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d28140)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
c000000000d28140-c000000000d28198: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a5f22)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
ffffffe0007a5f22-ffffffe0007a5fa8: devlink_param_driverinit_value_set (STB_GLOBAL)
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
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81927540)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
ffffffff81927540-ffffffff8192756a: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e12f0)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
ffffffff818e12f0-ffffffff818e131a: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819786d0)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
ffffffff819786d0-ffffffff819786fa: devlink_param_driverinit_value_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_param_driverinit_value_set(struct devlink *devlink, u32 param_id, union devlink_param_value init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199abc0)
Location: net/core/devlink.c:7258
Inline: False
```
**Symbols:**

```
ffffffff8199abc0-ffffffff8199abea: devlink_param_driverinit_value_set (STB_GLOBAL)
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
