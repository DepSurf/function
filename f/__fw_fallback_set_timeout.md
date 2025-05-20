# Function: <code>__fw_fallback_set_timeout</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b0dc)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff816bb95c)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff816f60fd)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff8171a4fd)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff817d651d)
Location: drivers/base/firmware_loader/fallback.c:32
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff817eaf4d)
Location: drivers/base/firmware_loader/fallback.c:32
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff817cf6cd)
Location: drivers/base/firmware_loader/fallback.c:32
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff81859e2d)
Location: drivers/base/firmware_loader/fallback.c:32
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff819a0ca5)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a10dc)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:timeout_store
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
In drivers/base/firmware_loader/fallback.c (ffffffff81b12925)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b12dcc)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:timeout_store
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
In drivers/base/firmware_loader/fallback.c (ffffffff81b60c15)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b610dc)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:timeout_store
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
In drivers/base/firmware_loader/fallback.c (ffffffff81bb4655)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4b6c)
Location: drivers/base/firmware_loader/sysfs.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:timeout_store
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
In drivers/base/firmware_loader/fallback.c (ffff80001090dde4)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (c09f6d60)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (c0000000009ae568)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffe0005925fc)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff816e082d)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bae6d)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8170defd)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
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
In drivers/base/firmware_loader/fallback.c (ffffffff81728b6d)
Location: drivers/base/firmware_loader/fallback.c:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_default_timeout
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
</details>
</li>
</ul>

## Differences
