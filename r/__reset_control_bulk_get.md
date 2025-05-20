# Function: <code>__reset_control_bulk_get</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732ad0)
Location: drivers/reset/core.c:954
Inline: False
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_bulk_get
```
**Symbols:**

```
ffffffff81732ad0-ffffffff81732c35: __reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b33e0)
Location: drivers/reset/core.c:954
Inline: False
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_bulk_get
```
**Symbols:**

```
ffffffff817b33e0-ffffffff817b3545: __reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818eefb0)
Location: drivers/reset/core.c:955
Inline: False
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_bulk_get
```
**Symbols:**

```
ffffffff818eefb0-ffffffff818ef11e: __reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a46c70)
Location: drivers/reset/core.c:955
Inline: False
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_bulk_get
```
**Symbols:**

```
ffffffff81a46c70-ffffffff81a46dde: __reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a90e10)
Location: drivers/reset/core.c:955
Inline: False
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_bulk_get
```
**Symbols:**

```
ffffffff81a90e10-ffffffff81a90f7e: __reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae3b60)
Location: drivers/reset/core.c:958
Inline: False
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_bulk_get
```
**Symbols:**

```
ffffffff81ae3b60-ffffffff81ae3c51: __reset_control_bulk_get (STB_GLOBAL)
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
