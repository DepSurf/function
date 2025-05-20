# Function: <code>get_next_rmap_item</code>

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
In mm/ksm.c (ffffffff811e5d6b)
Location: mm/ksm.c:1526
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81204a1b)
Location: mm/ksm.c:1498
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81216b0f)
Location: mm/ksm.c:1544
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81222522)
Location: mm/ksm.c:2110
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff8123d894)
Location: mm/ksm.c:2124
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81260e6e)
Location: mm/ksm.c:2182
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81275645)
Location: mm/ksm.c:2180
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81292049)
Location: mm/ksm.c:2206
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812a1dc9)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rmap_item *get_next_rmap_item(struct mm_slot *mm_slot, struct rmap_item **rmap_list, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d4770)
Location: mm/ksm.c:2196
Inline: False
Direct callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
**Symbols:**

```
ffffffff812d4770-ffffffff812d4834: get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rmap_item *get_next_rmap_item(struct mm_slot *mm_slot, struct rmap_item **rmap_list, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e0150)
Location: mm/ksm.c:2197
Inline: False
Direct callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
**Symbols:**

```
ffffffff812e0150-ffffffff812e0214: get_next_rmap_item (STB_LOCAL)
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
In mm/ksm.c (ffffffff812e8c5d)
Location: mm/ksm.c:2193
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
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
In mm/ksm.c (ffffffff81330b8a)
Location: mm/ksm.c:2189
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
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
In mm/ksm.c (ffffffff813a17d2)
Location: mm/ksm.c:2201
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
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
In mm/ksm.c (ffffffff814207e0)
Location: mm/ksm.c:2217
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
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
In mm/ksm.c (ffffffff814554a3)
Location: mm/ksm.c:2266
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
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
In mm/ksm.c (ffffffff8148f3b5)
Location: mm/ksm.c:2465
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
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
In mm/ksm.c (0)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (c05466a0)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
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
In mm/ksm.c (c00000000041cb3c)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
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
In mm/ksm.c (ffffffe000234fc6)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
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
In mm/ksm.c (ffffffff8129a3a9)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff8128bf69)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812981b9)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812a7f55)
Location: mm/ksm.c:2188
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
