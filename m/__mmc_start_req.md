# Function: <code>__mmc_start_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __mmc_start_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bf250)
Location: drivers/mmc/core/core.c:412
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
```
**Symbols:**

```
ffffffff816bf250-ffffffff816bf2c1: __mmc_start_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __mmc_start_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81721c60)
Location: drivers/mmc/core/core.c:413
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
```
**Symbols:**

```
ffffffff81721c60-ffffffff81721cd1: __mmc_start_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81754d34)
Location: drivers/mmc/core/core.c:466
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817728c4)
Location: drivers/mmc/core/core.c:421
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e8434)
Location: drivers/mmc/core/core.c:426
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81831835)
Location: drivers/mmc/core/core.c:380
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185d815)
Location: drivers/mmc/core/core.c:380
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a1455)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d3745)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a5e15)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8bdc)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198d8ac)
Location: drivers/mmc/core/core.c:379
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a38efc)
Location: drivers/mmc/core/core.c:379
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba5fab)
Location: drivers/mmc/core/core.c:379
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d482fb)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db2bfb)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6af8b)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2cca4)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c07ff8)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c25ad8)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000706d0c)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81877105)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c85a5)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e50c5)
Location: drivers/mmc/core/core.c:378
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
