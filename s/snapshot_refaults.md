# Function: <code>snapshot_refaults</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cfe70)
Location: mm/vmscan.c:2788
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811cfe70-ffffffff811cff68: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e5320)
Location: mm/vmscan.c:2812
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811e5320-ffffffff811e5403: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81205fd0)
Location: mm/vmscan.c:2820
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81205fd0-ffffffff8120606f: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812189a0)
Location: mm/vmscan.c:2987
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812189a0-ffffffff81218a3f: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228cf0)
Location: mm/vmscan.c:2952
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81228cf0-ffffffff81228ddb: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81236b90)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81236b90-ffffffff81236c7b: snapshot_refaults (STB_LOCAL)
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
In mm/vmscan.c (ffffffff81269b5d)
Location: mm/vmscan.c:2991
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff8127464d)
Location: mm/vmscan.c:2993
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff81279940)
Location: mm/vmscan.c:3191
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff812b7810)
Location: mm/vmscan.c:3352
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff81312684)
Location: mm/vmscan.c:3495
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff813859a0)
Location: mm/vmscan.c:6427
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff813b8c80)
Location: mm/vmscan.c:6790
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff813e1c80)
Location: mm/vmscan.c:6157
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c63e0)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffff8000102c63e0-ffff8000102c64f8: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f1d34)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c04f1d34-c04f1e3c: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000383040)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c000000000383040-c0000000003831c8: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e7374)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffe0001e7374-ffffffe0001e7490: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122f1e0)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8122f1e0-ffffffff8122f2cb: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812222a0)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812222a0-ffffffff8122238b: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122cf80)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8122cf80-ffffffff8122d06b: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void snapshot_refaults(struct mem_cgroup *root_memcg, pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123c3c0)
Location: mm/vmscan.c:3038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8123c3c0-ffffffff8123c4ab: snapshot_refaults (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
