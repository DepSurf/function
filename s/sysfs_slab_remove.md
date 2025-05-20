# Function: <code>sysfs_slab_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_slab_remove(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eefa0)
Location: mm/slub.c:5428
Inline: False
Direct callers:
  - mm/slab_common.c:release_caches
```
**Symbols:**

```
ffffffff811eefa0-ffffffff811eefe7: sysfs_slab_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_slab_remove(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120e250)
Location: mm/slub.c:5655
Inline: False
Direct callers:
  - mm/slab_common.c:release_caches
```
**Symbols:**

```
ffffffff8120e250-ffffffff8120e297: sysfs_slab_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_slab_remove(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81220290)
Location: mm/slub.c:5624
Inline: False
Direct callers:
  - mm/slab_common.c:release_caches
```
**Symbols:**

```
ffffffff81220290-ffffffff812202d7: sysfs_slab_remove (STB_GLOBAL)
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
In mm/slub.c (ffffffff8122ae50)
Location: mm/slub.c:5719
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81246550)
Location: mm/slub.c:5737
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81269910)
Location: mm/slub.c:5741
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8127e1e0)
Location: mm/slub.c:5792
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8129a5d6)
Location: mm/slub.c:5783
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812aa496)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812df1b6)
Location: mm/slub.c:5857
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034c29c)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (c054fe98)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (c00000000042bc60)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffe00023d438)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a2a76)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81294546)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a0886)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812b09c6)
Location: mm/slub.c:5810
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
