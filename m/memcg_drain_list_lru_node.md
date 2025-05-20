# Function: <code>memcg_drain_list_lru_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811b9a79)
Location: mm/list_lru.c:481
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811d3e09)
Location: mm/list_lru.c:481
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff811e3cc9)
Location: mm/list_lru.c:481
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff811ee189)
Location: mm/list_lru.c:479
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff812045f9)
Location: mm/list_lru.c:480
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff8122538d)
Location: mm/list_lru.c:503
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff812384b8)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff81249a92)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff81257ee2)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcg_drain_list_lru_node(struct list_lru *lru, int nid, int src_idx, struct mem_cgroup *dst_memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81285e60)
Location: mm/list_lru.c:531
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
**Symbols:**

```
ffffffff81285e60-ffffffff81285f60: memcg_drain_list_lru_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcg_drain_list_lru_node(struct list_lru *lru, int nid, int src_idx, struct mem_cgroup *dst_memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81290120)
Location: mm/list_lru.c:531
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
**Symbols:**

```
ffffffff81290120-ffffffff81290209: memcg_drain_list_lru_node (STB_LOCAL)
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
In mm/list_lru.c (ffffffff81295dde)
Location: mm/list_lru.c:523
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff812d648a)
Location: mm/list_lru.c:523
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
</details>
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
In mm/list_lru.c (ffff8000102efa88)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (c05132f8)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (c0000000003b42e0)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffe0002035da)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff81250532)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff812434bc)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff8124e2d2)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
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
In mm/list_lru.c (ffffffff8125dc45)
Location: mm/list_lru.c:541
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
