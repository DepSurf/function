# Function: <code>devlink_dpipe_table_counter_enabled</code>

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
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946dc0)
Location: net/core/devlink.c:6001
Inline: False
```
**Symbols:**

```
ffffffff81946dc0-ffffffff81946de4: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b9e0)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
ffffffff8197b9e0-ffffffff8197ba04: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a53650)
Location: net/core/devlink.c:7635
Inline: False
```
**Symbols:**

```
ffffffff81a53650-ffffffff81a536aa: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59dd0)
Location: net/core/devlink.c:8523
Inline: False
```
**Symbols:**

```
ffffffff81a59dd0-ffffffff81a59e3c: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3cf20)
Location: net/core/devlink.c:8782
Inline: False
```
**Symbols:**

```
ffffffff81a3cf20-ffffffff81a3cf8c: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:9627
Inline: False
```
**Symbols:**

```
ffffffff81d38464-ffffffff81d38479: devlink_dpipe_table_counter_enabled.cold (STB_LOCAL)
ffffffff81af3970-ffffffff81af39ea: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:10491
Inline: False
```
**Symbols:**

```
ffffffff81f04e4b-ffffffff81f04e5f: devlink_dpipe_table_counter_enabled.cold (STB_LOCAL)
ffffffff81c77ba0-ffffffff81c77c2c: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:11215
Inline: False
```
**Symbols:**

```
ffffffff820ace34-ffffffff820ace48: devlink_dpipe_table_counter_enabled.cold (STB_LOCAL)
ffffffff81e306b0-ffffffff81e3073c: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:7772
Inline: False
```
**Symbols:**

```
ffffffff821363e2-ffffffff821363f6: devlink_dpipe_table_counter_enabled.cold (STB_LOCAL)
ffffffff820334a0-ffffffff8203352c: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dpipe.c (0)
Location: net/devlink/dpipe.c:814
Inline: False
```
**Symbols:**

```
ffffffff822180db-ffffffff822180ef: devlink_dpipe_table_counter_enabled.cold (STB_LOCAL)
ffffffff8210a890-ffffffff8210a91c: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
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
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c233a0)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
ffff800010c233a0-ffff800010c233ec: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a984)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
c0d3a984-c0d3a9ac: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d16b90)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
c000000000d16b90-c000000000d16be4: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079bbd4)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
ffffffe00079bbd4-ffffffe00079bc1c: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
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
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b850)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
ffffffff8191b850-ffffffff8191b874: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5600)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
ffffffff818d5600-ffffffff818d5624: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c9e0)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
ffffffff8196c9e0-ffffffff8196ca04: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool devlink_dpipe_table_counter_enabled(struct devlink *devlink, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819900d0)
Location: net/core/devlink.c:6698
Inline: False
```
**Symbols:**

```
ffffffff819900d0-ffffffff8199010d: devlink_dpipe_table_counter_enabled (STB_GLOBAL)
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
