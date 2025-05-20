# Function: <code>pcpu_get_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff811b0a10)
Location: mm/percpu-vm.c:33
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff811b0a10-ffffffff811b0a48: pcpu_get_pages.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff811c9c30)
Location: mm/percpu-vm.c:33
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff811c9c30-ffffffff811c9c68: pcpu_get_pages.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff811d9d20)
Location: mm/percpu-vm.c:33
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff811d9d20-ffffffff811d9d58: pcpu_get_pages.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e33a0)
Location: mm/percpu-vm.c:32
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff811e33a0-ffffffff811e33d9: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f8bd0)
Location: mm/percpu-vm.c:32
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff811f8bd0-ffffffff811f8c0b: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121a5d0)
Location: mm/percpu-vm.c:32
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff8121a5d0-ffffffff8121a60d: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122d540)
Location: mm/percpu-vm.c:32
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff8122d540-ffffffff8122d57d: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123d270)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff8123d270-ffffffff8123d2ad: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124b6c0)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff8124b6c0-ffffffff8124b6fd: pcpu_get_pages (STB_LOCAL)
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
In mm/percpu.c (ffffffff8127a95a)
Location: mm/percpu-vm.c:31
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff812850ef)
Location: mm/percpu-vm.c:31
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8128aebc)
Location: mm/percpu-vm.c:32
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff812ca30f)
Location: mm/percpu-vm.c:32
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff81326c9a)
Location: mm/percpu-vm.c:32
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8139b955)
Location: mm/percpu-vm.c:32
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff813ce935)
Location: mm/percpu-vm.c:32
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff813f9495)
Location: mm/percpu-vm.c:32
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
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
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e0ea8)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffff8000102e0ea8-ffff8000102e0f04: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0505b0c)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
c0505b0c-c0505b5c: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a1270)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
c0000000003a1270-c0000000003a12d8: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f86e8)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffe0001f86e8-ffffffe0001f873e: pcpu_get_pages (STB_LOCAL)
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
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81243d10)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81243d10-ffffffff81243d4d: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81236ce0)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81236ce0-ffffffff81236d1d: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81241ab0)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81241ab0-ffffffff81241aed: pcpu_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page **pcpu_get_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81251250)
Location: mm/percpu-vm.c:31
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81251250-ffffffff8125128d: pcpu_get_pages (STB_LOCAL)
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
