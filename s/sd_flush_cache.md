# Function: <code>sd_flush_cache</code>

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
int sd_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1298
Inline: False
```
**Symbols:**

```
ffffffff81a431d0-ffffffff81a432eb: sd_flush_cache (STB_LOCAL)
ffffffff81d2e1ff-ffffffff81d2e245: sd_flush_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sd_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1305
Inline: False
```
**Symbols:**

```
ffffffff81bb0bb0-ffffffff81bb0cdc: sd_flush_cache (STB_LOCAL)
ffffffff81efa62e-ffffffff81efa67a: sd_flush_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sd_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d54950)
Location: drivers/mmc/core/sd.c:1312
Inline: False
```
**Symbols:**

```
ffffffff81d54950-ffffffff81d54aba: sd_flush_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sd_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dbf2d0)
Location: drivers/mmc/core/sd.c:1312
Inline: False
```
**Symbols:**

```
ffffffff81dbf2d0-ffffffff81dbf43a: sd_flush_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sd_flush_cache(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e77980)
Location: drivers/mmc/core/sd.c:1312
Inline: False
```
**Symbols:**

```
ffffffff81e77980-ffffffff81e77b19: sd_flush_cache (STB_LOCAL)
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
