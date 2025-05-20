# Function: <code>_mmc_cache_enabled</code>

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
bool _mmc_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819916d0)
Location: drivers/mmc/core/mmc.c:2032
Inline: False
```
**Symbols:**

```
ffffffff819916d0-ffffffff819916fa: _mmc_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool _mmc_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81a3d275)
Location: drivers/mmc/core/mmc.c:2036
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
```
**Symbols:**

```
ffffffff81a3ceb0-ffffffff81a3ceda: _mmc_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool _mmc_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81baa205)
Location: drivers/mmc/core/mmc.c:2071
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
```
**Symbols:**

```
ffffffff81ba9fa0-ffffffff81ba9fda: _mmc_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool _mmc_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4d155)
Location: drivers/mmc/core/mmc.c:2071
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
```
**Symbols:**

```
ffffffff81d4ce90-ffffffff81d4ceca: _mmc_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool _mmc_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81db7ab5)
Location: drivers/mmc/core/mmc.c:2071
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
```
**Symbols:**

```
ffffffff81db77f0-ffffffff81db782a: _mmc_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool _mmc_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e7145e)
Location: drivers/mmc/core/mmc.c:2092
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
```
**Symbols:**

```
ffffffff81e6fcc0-ffffffff81e6fcfa: _mmc_cache_enabled (STB_LOCAL)
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
