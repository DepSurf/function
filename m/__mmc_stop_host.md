# Function: <code>__mmc_stop_host</code>

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
void __mmc_stop_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3b845)
Location: drivers/mmc/core/core.c:2267
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/host.c:mmc_host_classdev_shutdown
```
**Symbols:**

```
ffffffff81a3b7f0-ffffffff81a3b835: __mmc_stop_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __mmc_stop_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba87d5)
Location: drivers/mmc/core/core.c:2269
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/host.c:mmc_host_classdev_shutdown
```
**Symbols:**

```
ffffffff81ba8780-ffffffff81ba87cf: __mmc_stop_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __mmc_stop_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4b055)
Location: drivers/mmc/core/core.c:2287
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/host.c:mmc_host_classdev_shutdown
```
**Symbols:**

```
ffffffff81d4aff0-ffffffff81d4b03f: __mmc_stop_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __mmc_stop_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db5905)
Location: drivers/mmc/core/core.c:2292
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/host.c:mmc_host_classdev_shutdown
```
**Symbols:**

```
ffffffff81db58a0-ffffffff81db58ef: __mmc_stop_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __mmc_stop_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6dd55)
Location: drivers/mmc/core/core.c:2297
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
Direct callers:
  - drivers/mmc/core/host.c:mmc_host_classdev_shutdown
```
**Symbols:**

```
ffffffff81e6dcf0-ffffffff81e6dd3f: __mmc_stop_host (STB_GLOBAL)
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
