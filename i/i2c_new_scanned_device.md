# Function: <code>i2c_new_scanned_device</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2210
Inline: False
```
**Symbols:**

```
ffffffff81943601-ffffffff81943618: i2c_new_scanned_device.cold (STB_LOCAL)
ffffffff81942e10-ffffffff81942f39: i2c_new_scanned_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2340
Inline: False
```
**Symbols:**

```
ffffffff81c24caa-ffffffff81c24cc1: i2c_new_scanned_device.cold (STB_LOCAL)
ffffffff819491f0-ffffffff81949319: i2c_new_scanned_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2400
Inline: False
```
**Symbols:**

```
ffffffff81c16d5a-ffffffff81c16d71: i2c_new_scanned_device.cold (STB_LOCAL)
ffffffff8192cb20-ffffffff8192cc49: i2c_new_scanned_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2401
Inline: False
```
**Symbols:**

```
ffffffff81d25a53-ffffffff81d25a6a: i2c_new_scanned_device.cold (STB_LOCAL)
ffffffff819cfcf0-ffffffff819cfe13: i2c_new_scanned_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2404
Inline: False
```
**Symbols:**

```
ffffffff81ef17d6-ffffffff81ef17ed: i2c_new_scanned_device.cold (STB_LOCAL)
ffffffff81b31bb0-ffffffff81b31cd7: i2c_new_scanned_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc67a0)
Location: drivers/i2c/i2c-core-base.c:2412
Inline: False
```
**Symbols:**

```
ffffffff81cc67a0-ffffffff81cc68e5: i2c_new_scanned_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2e440)
Location: drivers/i2c/i2c-core-base.c:2525
Inline: False
```
**Symbols:**

```
ffffffff81d2e440-ffffffff81d2e585: i2c_new_scanned_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct i2c_client *i2c_new_scanned_device(struct i2c_adapter *adap, struct i2c_board_info *info, const short unsigned int *addr_list, int (*probe)(struct i2c_adapter *, short unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de43f0)
Location: drivers/i2c/i2c-core-base.c:2543
Inline: False
```
**Symbols:**

```
ffffffff81de43f0-ffffffff81de4535: i2c_new_scanned_device (STB_GLOBAL)
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
