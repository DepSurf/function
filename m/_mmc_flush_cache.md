# Function: <code>_mmc_flush_cache</code>

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
int _mmc_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2045
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81a3d270-ffffffff81a3d2ca: _mmc_flush_cache (STB_LOCAL)
ffffffff81d2d6e2-ffffffff81d2d705: _mmc_flush_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _mmc_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2080
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81baa200-ffffffff81baa26a: _mmc_flush_cache (STB_LOCAL)
ffffffff81ef9a8f-ffffffff81ef9ab2: _mmc_flush_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _mmc_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4d150)
Location: drivers/mmc/core/mmc.c:2080
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81d4d150-ffffffff81d4d1e7: _mmc_flush_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _mmc_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81db7ab0)
Location: drivers/mmc/core/mmc.c:2080
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81db7ab0-ffffffff81db7b47: _mmc_flush_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _mmc_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2101
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81e71420-ffffffff81e714ef: _mmc_flush_cache (STB_LOCAL)
ffffffff8220c9ac-ffffffff8220c9c1: _mmc_flush_cache.cold (STB_LOCAL)
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
