# Function: <code>sd_cache_enabled</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sd_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81a431f0)
Location: drivers/mmc/core/sd.c:1293
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81a41fe0-ffffffff81a41fff: sd_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool sd_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81bb0bcf)
Location: drivers/mmc/core/sd.c:1300
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81baf760-ffffffff81baf785: sd_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool sd_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d54970)
Location: drivers/mmc/core/sd.c:1307
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81d53270-ffffffff81d53295: sd_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool sd_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dbf2f0)
Location: drivers/mmc/core/sd.c:1307
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81dbdc40-ffffffff81dbdc65: sd_cache_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool sd_cache_enabled(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e779a0)
Location: drivers/mmc/core/sd.c:1307
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81e76270-ffffffff81e76295: sd_cache_enabled (STB_LOCAL)
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
