# Function: <code>mmc_busy_cb</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_busy_cb(void *cb_data, bool *busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:431
Inline: False
```
**Symbols:**

```
ffffffff81a40d80-ffffffff81a40eb3: mmc_busy_cb (STB_LOCAL)
ffffffff81d2dee3-ffffffff81d2def8: mmc_busy_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_busy_cb(void *cb_data, bool *busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:460
Inline: False
```
**Symbols:**

```
ffffffff81badf40-ffffffff81bae062: mmc_busy_cb (STB_LOCAL)
ffffffff81efa1e7-ffffffff81efa202: mmc_busy_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_busy_cb(void *cb_data, bool *busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:460
Inline: False
```
**Symbols:**

```
ffffffff81d51360-ffffffff81d51482: mmc_busy_cb (STB_LOCAL)
ffffffff820a9984-ffffffff820a999f: mmc_busy_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_busy_cb(void *cb_data, bool *busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:460
Inline: False
```
**Symbols:**

```
ffffffff81dbbd80-ffffffff81dbbeae: mmc_busy_cb (STB_LOCAL)
ffffffff8212ad66-ffffffff8212ad81: mmc_busy_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_busy_cb(void *cb_data, bool *busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:460
Inline: False
```
**Symbols:**

```
ffffffff81e74350-ffffffff81e7447e: mmc_busy_cb (STB_LOCAL)
ffffffff8220cb23-ffffffff8220cb3e: mmc_busy_cb.cold (STB_LOCAL)
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
