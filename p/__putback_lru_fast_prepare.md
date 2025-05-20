# Function: <code>__putback_lru_fast_prepare</code>

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
In mm/mlock.c (ffffffff811c2f0c)
Location: mm/mlock.c:232
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff811deb87)
Location: mm/mlock.c:237
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff811ee9a7)
Location: mm/mlock.c:240
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff811f99ac)
Location: mm/mlock.c:239
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff81211dd8)
Location: mm/mlock.c:240
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff81232b8b)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff8124635b)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff81258595)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff81266a65)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __putback_lru_fast_prepare(struct page *page, struct pagevec *pvec, int *pgrescued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81296680)
Location: mm/mlock.c:246
Inline: False
Direct callers:
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff81296680-ffffffff81296739: __putback_lru_fast_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __putback_lru_fast_prepare(struct page *page, struct pagevec *pvec, int *pgrescued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a15f0)
Location: mm/mlock.c:215
Inline: False
Direct callers:
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff812a15f0-ffffffff812a16b9: __putback_lru_fast_prepare (STB_LOCAL)
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
In mm/mlock.c (ffffffff812a7388)
Location: mm/mlock.c:215
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff812e89c5)
Location: mm/mlock.c:216
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffff8000102fda64)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (c051ce88)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (c0000000003c8fa0)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffe00020c252)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff8125f0b5)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff812514df)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff8125ce55)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/mlock.c (ffffffff8126c822)
Location: mm/mlock.c:246
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
