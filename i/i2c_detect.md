# Function: <code>i2c_detect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167d36c)
Location: drivers/i2c/i2c-core.c:2443
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de10c)
Location: drivers/i2c/i2c-core.c:2648
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170e4cc)
Location: drivers/i2c/i2c-core.c:2935
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81721630)
Location: drivers/i2c/i2c-core-base.c:2121
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81721630-ffffffff8172193b: i2c_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81792960)
Location: drivers/i2c/i2c-core-base.c:2145
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81792960-ffffffff81792c82: i2c_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d5630)
Location: drivers/i2c/i2c-core-base.c:2131
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff817d5630-ffffffff817d593b: i2c_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fc610)
Location: drivers/i2c/i2c-core-base.c:2131
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff817fc610-ffffffff817fc915: i2c_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2224
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff8183cc40-ffffffff8183cee9: i2c_detect (STB_LOCAL)
ffffffff8183dadd-ffffffff8183db4f: i2c_detect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2229
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff8186e640-ffffffff8186e8e9: i2c_detect (STB_LOCAL)
ffffffff8186f49c-ffffffff8186f50e: i2c_detect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819427e0)
Location: drivers/i2c/i2c-core-base.c:2159
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff819427e0-ffffffff8194290d: i2c_detect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81948b50)
Location: drivers/i2c/i2c-core-base.c:2289
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81948b50-ffffffff81948c7d: i2c_detect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192c4d0)
Location: drivers/i2c/i2c-core-base.c:2349
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff8192c4d0-ffffffff8192c5fd: i2c_detect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cf690)
Location: drivers/i2c/i2c-core-base.c:2350
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff819cf690-ffffffff819cf7b7: i2c_detect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b31490)
Location: drivers/i2c/i2c-core-base.c:2353
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81b31490-ffffffff81b315d9: i2c_detect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5fb0)
Location: drivers/i2c/i2c-core-base.c:2361
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81cc5fb0-ffffffff81cc60f9: i2c_detect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2dc40)
Location: drivers/i2c/i2c-core-base.c:2474
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81d2dc40-ffffffff81d2dd89: i2c_detect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de3b80)
Location: drivers/i2c/i2c-core-base.c:2492
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81de3b80-ffffffff81de3cf8: i2c_detect.isra.0 (STB_LOCAL)
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
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab1d70)
Location: drivers/i2c/i2c-core-base.c:2229
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffff800010ab1d70-ffff800010ab205c: i2c_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93428)
Location: drivers/i2c/i2c-core-base.c:2229
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
c0b93428-c0b9373c: i2c_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b95320)
Location: drivers/i2c/i2c-core-base.c:2229
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
c000000000b95320-c000000000b9576c: i2c_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9b02)
Location: drivers/i2c/i2c-core-base.c:2229
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffe0006b9b02-ffffffe0006b9da2: i2c_detect (STB_LOCAL)
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
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2229
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff818627d0-ffffffff81862a79: i2c_detect (STB_LOCAL)
ffffffff8186362c-ffffffff8186369e: i2c_detect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_detect(struct i2c_adapter *adapter, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2229
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff8187da30-ffffffff8187dcd9: i2c_detect (STB_LOCAL)
ffffffff8187e88c-ffffffff8187e8fe: i2c_detect.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
