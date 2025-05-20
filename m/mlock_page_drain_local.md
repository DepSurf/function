# Function: <code>mlock_page_drain_local</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mlock_page_drain_local();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8134bf20)
Location: mm/mlock.c:213
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff8134bf20-ffffffff8134bf69: mlock_page_drain_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mlock_page_drain_local();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c4ab0)
Location: mm/mlock.c:213
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff813c4ab0-ffffffff813c4af9: mlock_page_drain_local (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
