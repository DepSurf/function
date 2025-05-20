# Function: <code>i2c_new_probed_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167c830)
Location: drivers/i2c/i2c-core.c:2495
Inline: False
```
**Symbols:**

```
ffffffff8167c830-ffffffff8167c94c: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dd740)
Location: drivers/i2c/i2c-core.c:2700
Inline: False
```
**Symbols:**

```
ffffffff816dd740-ffffffff816dd865: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170daa0)
Location: drivers/i2c/i2c-core.c:2987
Inline: False
```
**Symbols:**

```
ffffffff8170daa0-ffffffff8170dbc5: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817219d0)
Location: drivers/i2c/i2c-core-base.c:2173
Inline: False
```
**Symbols:**

```
ffffffff817219d0-ffffffff81721afa: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81792d20)
Location: drivers/i2c/i2c-core-base.c:2197
Inline: False
```
**Symbols:**

```
ffffffff81792d20-ffffffff81792e4c: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d5380)
Location: drivers/i2c/i2c-core-base.c:2183
Inline: False
```
**Symbols:**

```
ffffffff817d5380-ffffffff817d5498: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fc4f0)
Location: drivers/i2c/i2c-core-base.c:2183
Inline: False
```
**Symbols:**

```
ffffffff817fc4f0-ffffffff817fc608: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2276
Inline: False
```
**Symbols:**

```
ffffffff8183dc2c-ffffffff8183dc43: i2c_new_probed_device.cold (STB_LOCAL)
ffffffff8183d400-ffffffff8183d514: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2281
Inline: False
```
**Symbols:**

```
ffffffff8186f5d2-ffffffff8186f5e9: i2c_new_probed_device.cold (STB_LOCAL)
ffffffff8186ee00-ffffffff8186ef14: i2c_new_probed_device (STB_GLOBAL)
```
</details>
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
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab2728)
Location: drivers/i2c/i2c-core-base.c:2281
Inline: False
```
**Symbols:**

```
ffff800010ab2728-ffff800010ab28a0: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93df4)
Location: drivers/i2c/i2c-core-base.c:2281
Inline: False
```
**Symbols:**

```
c0b93df4-c0b93f5c: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b96060)
Location: drivers/i2c/i2c-core-base.c:2281
Inline: False
```
**Symbols:**

```
c000000000b96060-c000000000b9626c: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba3fa)
Location: drivers/i2c/i2c-core-base.c:2281
Inline: False
```
**Symbols:**

```
ffffffe0006ba3fa-ffffffe0006ba55e: i2c_new_probed_device (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2281
Inline: False
```
**Symbols:**

```
ffffffff81863762-ffffffff81863779: i2c_new_probed_device.cold (STB_LOCAL)
ffffffff81862f90-ffffffff818630a4: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_probed_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2281
Inline: False
```
**Symbols:**

```
ffffffff8187e9c2-ffffffff8187e9d9: i2c_new_probed_device.cold (STB_LOCAL)
ffffffff8187e1f0-ffffffff8187e304: i2c_new_probed_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
