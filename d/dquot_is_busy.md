# Function: <code>dquot_is_busy</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81367016)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff813aecd6)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff813c02c6)
Location: include/linux/quotaops.h:55
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff813c6fd6)
Location: include/linux/quotaops.h:55
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff8141731c)
Location: include/linux/quotaops.h:55
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff8148eb4e)
Location: include/linux/quotaops.h:55
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff8152267e)
Location: include/linux/quotaops.h:56
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff8155a71e)
Location: include/linux/quotaops.h:56
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In mm/shmem_quota.c (ffffffff81408cdb)
Location: include/linux/quotaops.h:56
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_release_dquot
```
```
In fs/quota/dquot.c (ffffffff81590ede)
Location: include/linux/quotaops.h:56
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffff80001042e9ac)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (c05f7d2c)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (c000000000540038)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffe0002cafe0)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff8135f5f6)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff81350296)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff8135d0c6)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
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
In fs/quota/dquot.c (ffffffff81370a66)
Location: include/linux/quotaops.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
```
</details>
</li>
</ul>

## Differences
