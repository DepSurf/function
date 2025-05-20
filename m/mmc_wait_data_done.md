# Function: <code>mmc_wait_data_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mmc_wait_data_done(struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bdab0)
Location: drivers/mmc/core/core.c:375
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_req
```
**Symbols:**

```
ffffffff816bdab0-ffffffff816bdade: mmc_wait_data_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_wait_data_done(struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81721b7c)
Location: drivers/mmc/core/core.c:376
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_req
```
**Symbols:**

```
ffffffff8171f6d0-ffffffff8171f6fe: mmc_wait_data_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mmc_wait_data_done(struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817549ea)
Location: drivers/mmc/core/core.c:410
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_req
```
**Symbols:**

```
ffffffff81751f60-ffffffff81751f8e: mmc_wait_data_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_wait_data_done(struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81772784)
Location: drivers/mmc/core/core.c:365
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_areq
```
**Symbols:**

```
ffffffff81770990-ffffffff817709be: mmc_wait_data_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_wait_data_done(struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e8fd0)
Location: drivers/mmc/core/core.c:370
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_areq
```
**Symbols:**

```
ffffffff817e6660-ffffffff817e668e: mmc_wait_data_done (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
