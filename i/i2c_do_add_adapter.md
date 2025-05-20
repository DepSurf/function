# Function: <code>i2c_do_add_adapter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i2c_do_add_adapter(struct i2c_driver *driver, struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167d350)
Location: drivers/i2c/i2c-core.c:1503
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:__process_new_adapter
```
**Symbols:**

```
ffffffff8167d350-ffffffff8167d677: i2c_do_add_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i2c_do_add_adapter(struct i2c_driver *driver, struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de0f0)
Location: drivers/i2c/i2c-core.c:1671
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:__process_new_adapter
```
**Symbols:**

```
ffffffff816de0f0-ffffffff816de3ef: i2c_do_add_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_do_add_adapter(struct i2c_driver *driver, struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170e4b0)
Location: drivers/i2c/i2c-core.c:1870
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:__process_new_adapter
```
**Symbols:**

```
ffffffff8170e4b0-ffffffff8170e7af: i2c_do_add_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817219a8)
Location: drivers/i2c/i2c-core-base.c:1112
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81720a10-ffffffff81720a57: i2c_do_add_adapter.part.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81792cf8)
Location: drivers/i2c/i2c-core-base.c:1129
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff81791d60-ffffffff81791dae: i2c_do_add_adapter.part.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d59a4)
Location: drivers/i2c/i2c-core-base.c:1108
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
Direct callers:
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
**Symbols:**

```
ffffffff817d46e0-ffffffff817d472e: i2c_do_add_adapter.part.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fc952)
Location: drivers/i2c/i2c-core-base.c:1120
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183cf22)
Location: drivers/i2c/i2c-core-base.c:1209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186e922)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81942922)
Location: drivers/i2c/i2c-core-base.c:1175
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81948c92)
Location: drivers/i2c/i2c-core-base.c:1303
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192c612)
Location: drivers/i2c/i2c-core-base.c:1337
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cf7d2)
Location: drivers/i2c/i2c-core-base.c:1338
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b315fa)
Location: drivers/i2c/i2c-core-base.c:1340
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff81cc612a)
Location: drivers/i2c/i2c-core-base.c:1334
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff81d2ddba)
Location: drivers/i2c/i2c-core-base.c:1378
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff81de3d2a)
Location: drivers/i2c/i2c-core-base.c:1388
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab20dc)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93794)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b957ec)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9e0e)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81862ab2)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187dd12)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__process_new_driver
  - drivers/i2c/i2c-core-base.c:__process_new_adapter
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
</ul>
