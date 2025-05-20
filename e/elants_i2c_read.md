# Function: <code>elants_i2c_read</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff816ffce0)
Location: drivers/input/touchscreen/elants_i2c.c:174
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff816ffce0-ffffffff816ffd3b: elants_i2c_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817155f0)
Location: drivers/input/touchscreen/elants_i2c.c:174
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff817155f0-ffffffff81715650: elants_i2c_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81786810)
Location: drivers/input/touchscreen/elants_i2c.c:175
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81786810-ffffffff81786870: elants_i2c_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c77b0)
Location: drivers/input/touchscreen/elants_i2c.c:174
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff817c77b0-ffffffff817c780f: elants_i2c_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817eee50)
Location: drivers/input/touchscreen/elants_i2c.c:175
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff817eee50-ffffffff817eeeaf: elants_i2c_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:170
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff8182fa40-ffffffff8182fa77: elants_i2c_read (STB_LOCAL)
ffffffff81830db6-ffffffff81830de4: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:170
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81861370-ffffffff818613a7: elants_i2c_read (STB_LOCAL)
ffffffff818626e6-ffffffff81862714: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935365)
Location: drivers/input/touchscreen/elants_i2c.c:177
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_write_page
```
**Symbols:**

```
ffffffff81934520-ffffffff81934557: elants_i2c_read (STB_LOCAL)
ffffffff81935b34-ffffffff81935b62: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c3d5)
Location: drivers/input/touchscreen/elants_i2c.c:182
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_write_page
```
**Symbols:**

```
ffffffff8193b580-ffffffff8193b5b7: elants_i2c_read (STB_LOCAL)
ffffffff81c23776-ffffffff81c237a4: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f967)
Location: drivers/input/touchscreen/elants_i2c.c:195
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff8191eb40-ffffffff8191eb77: elants_i2c_read (STB_LOCAL)
ffffffff81c15832-ffffffff81c15860: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2717)
Location: drivers/input/touchscreen/elants_i2c.c:208
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff819c18f0-ffffffff819c1927: elants_i2c_read (STB_LOCAL)
ffffffff81d241d3-ffffffff81d24201: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b22af4)
Location: drivers/input/touchscreen/elants_i2c.c:208
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff81b21bf0-ffffffff81b21c33: elants_i2c_read (STB_LOCAL)
ffffffff81ef0016-ffffffff81ef0044: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb6301)
Location: drivers/input/touchscreen/elants_i2c.c:208
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d98d)
Location: drivers/input/touchscreen/elants_i2c.c:208
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd368d)
Location: drivers/input/touchscreen/elants_i2c.c:208
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:170
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81855500-ffffffff81855537: elants_i2c_read (STB_LOCAL)
ffffffff81856876-ffffffff818568a4: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int elants_i2c_read(struct i2c_client *client, void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:170
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81870630-ffffffff81870667: elants_i2c_read (STB_LOCAL)
ffffffff818719a6-ffffffff818719d4: elants_i2c_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
