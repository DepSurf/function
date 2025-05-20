# Function: <code>pagevec_move_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119dbd0)
Location: mm/swap.c:463
Inline: False
Direct callers:
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:lru_add_drain_cpu
```
**Symbols:**

```
ffffffff8119dbd0-ffffffff8119dc25: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b2e20)
Location: mm/swap.c:222
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff811b2e20-ffffffff811b2e75: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3490)
Location: mm/swap.c:223
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff811c3490-ffffffff811c34e5: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cb900)
Location: mm/swap.c:234
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff811cb900-ffffffff811cb955: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e0cf0)
Location: mm/swap.c:234
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff811e0cf0-ffffffff811e0d45: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202580)
Location: mm/swap.c:235
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff81202580-ffffffff812025d5: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81214f00)
Location: mm/swap.c:234
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff81214f00-ffffffff81214f55: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812241b0)
Location: mm/swap.c:235
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff812241b0-ffffffff81224205: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81231f40)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff81231f40-ffffffff81231f95: pagevec_move_tail (STB_LOCAL)
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
In mm/swap.c (ffffffff812601e0)
Location: mm/swap.c:252
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c1cd0)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffff8000102c1cd0-ffff8000102c1d4c: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ecebc)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
c04ecebc-c04ecf40: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037bbb0)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
c00000000037bbb0-c00000000037bc38: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e300e)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffe0001e300e-ffffffe0001e3070: pagevec_move_tail (STB_LOCAL)
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
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122a590)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff8122a590-ffffffff8122a5e5: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121d6b0)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff8121d6b0-ffffffff8121d705: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228330)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff81228330-ffffffff81228385: pagevec_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pagevec_move_tail(struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81237670)
Location: mm/swap.c:236
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff81237670-ffffffff812376c5: pagevec_move_tail (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
