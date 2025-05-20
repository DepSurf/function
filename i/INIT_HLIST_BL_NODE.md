# Function: <code>INIT_HLIST_BL_NODE</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225860)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff8126cc18)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124d95b)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff8129892a)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260a3b)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff812ad3aa)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e20f)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff812ba861)
Location: include/linux/list_bl.h:43
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290b2f)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff812de141)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b72a5)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff8130a23d)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc480)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff8131fb6d)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e9071)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff813473d9)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fac11)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff8135f53f)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813309d1)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff813a511f)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
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
In fs/dcache.c (ffffffff8133c341)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff813b5e7f)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
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
In fs/dcache.c (ffffffff813427d1)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff813bce5f)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
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
In fs/dcache.c (ffffffff813900f1)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff8140ca1f)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
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
In fs/dcache.c (ffffffff81411cd9)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff81481b99)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
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
In fs/dcache.c (ffffffff8149ca39)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
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
In fs/dcache.c (ffffffff814d1de4)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
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
In fs/dcache.c (ffffffff8150478d)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a9e88)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffff800010424ed8)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058af24)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (c05edc6c)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a4c34)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (c0000000005343b0)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026fca4)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffe0002c41ba)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f31f1)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff81357b1f)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e3e21)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff813487cf)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1001)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff813555ef)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813021c1)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/mbcache.c (ffffffff81368bcf)
Location: include/linux/list_bl.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
</details>
</li>
</ul>

## Differences
