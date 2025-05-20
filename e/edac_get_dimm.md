# Function: <code>edac_get_dimm</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198824d)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ue_error
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d786)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/edac/ghes_edac.c:ghes_edac_dmidecode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198c17d)
Location: include/linux/edac.h:626
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ue_error
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81c28da0)
Location: include/linux/edac.h:626
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81970c68)
Location: include/linux/edac.h:626
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81c1af8c)
Location: include/linux/edac.h:626
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81a19585)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81d2aed3)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81b8224d)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81ef7099)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d20b37)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25d21)
Location: include/linux/edac.h:635
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d89d47)
Location: include/linux/edac.h:635
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8ef4a)
Location: include/linux/edac.h:635
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81e41497)
Location: include/linux/edac.h:638
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff81e4685a)
Location: include/linux/edac.h:638
Inline: True
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
