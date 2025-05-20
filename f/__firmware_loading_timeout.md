# Function: <code>__firmware_loading_timeout</code>

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
In drivers/base/firmware_loader/fallback.c (ffffffff8169ba49)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff816bc2e8)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff816f694e)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff8171ad47)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff817d6bc5)
Location: drivers/base/firmware_loader/fallback.c:26
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff817eb792)
Location: drivers/base/firmware_loader/fallback.c:26
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff817cff72)
Location: drivers/base/firmware_loader/fallback.c:26
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff8185a792)
Location: drivers/base/firmware_loader/fallback.c:26
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff819a0df9)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a14d9)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff81b12a99)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b12f09)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff81b60d89)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b61219)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff81bb4819)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4ca9)
Location: drivers/base/firmware_loader/sysfs.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffff80001090e62c)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (c09f749c)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (c0000000009aee68)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffe000592cc0)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff816e1077)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff816bb6b7)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff8170e747)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
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
In drivers/base/firmware_loader/fallback.c (ffffffff81729367)
Location: drivers/base/firmware_loader/fallback.c:23
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:timeout_show
  - drivers/base/firmware_loader/fallback.c:fw_fallback_set_cache_timeout
```
</details>
</li>
</ul>

## Differences
