# Function: <code>reset_control_bulk_deassert</code>

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
int reset_control_bulk_deassert(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81733400)
Location: drivers/reset/core.c:578
Inline: False
```
**Symbols:**

```
ffffffff81733400-ffffffff8173349b: reset_control_bulk_deassert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reset_control_bulk_deassert(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b3b80)
Location: drivers/reset/core.c:578
Inline: False
```
**Symbols:**

```
ffffffff817b3b80-ffffffff817b3c1b: reset_control_bulk_deassert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int reset_control_bulk_deassert(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818ef980)
Location: drivers/reset/core.c:579
Inline: False
```
**Symbols:**

```
ffffffff818ef980-ffffffff818efa28: reset_control_bulk_deassert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reset_control_bulk_deassert(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a476d0)
Location: drivers/reset/core.c:579
Inline: False
```
**Symbols:**

```
ffffffff81a476d0-ffffffff81a47778: reset_control_bulk_deassert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reset_control_bulk_deassert(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a91880)
Location: drivers/reset/core.c:579
Inline: False
```
**Symbols:**

```
ffffffff81a91880-ffffffff81a91928: reset_control_bulk_deassert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reset_control_bulk_deassert(int num_rstcs, struct reset_control_bulk_data *rstcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae41f0)
Location: drivers/reset/core.c:579
Inline: False
```
**Symbols:**

```
ffffffff81ae41f0-ffffffff81ae4298: reset_control_bulk_deassert (STB_GLOBAL)
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
