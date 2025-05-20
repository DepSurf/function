# Function: <code>reset_control_bulk_put</code>

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
void reset_control_bulk_put(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732d00)
Location: drivers/reset/core.c:1016
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_bulk_release
```
**Symbols:**

```
ffffffff81732d00-ffffffff81732dd4: reset_control_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reset_control_bulk_put(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b3610)
Location: drivers/reset/core.c:1016
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_bulk_release
```
**Symbols:**

```
ffffffff817b3610-ffffffff817b36e4: reset_control_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reset_control_bulk_put(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818eee90)
Location: drivers/reset/core.c:1017
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_bulk_release
```
**Symbols:**

```
ffffffff818eee90-ffffffff818eef77: reset_control_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reset_control_bulk_put(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a46b30)
Location: drivers/reset/core.c:1017
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_bulk_release
```
**Symbols:**

```
ffffffff81a46b30-ffffffff81a46c17: reset_control_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reset_control_bulk_put(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a90cd0)
Location: drivers/reset/core.c:1017
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_bulk_release
```
**Symbols:**

```
ffffffff81a90cd0-ffffffff81a90db7: reset_control_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void reset_control_bulk_put(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae3d8b)
Location: drivers/reset/core.c:1020
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_bulk_release
```
**Symbols:**

```
ffffffff81ae38f0-ffffffff81ae394c: reset_control_bulk_put (STB_GLOBAL)
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
