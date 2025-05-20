# Function: <code>__fprop_add_percpu_max</code>

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
void __fprop_add_percpu_max(struct fprop_global *p, struct fprop_local_percpu *pl, int max_frac, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff81777ce0)
Location: lib/flex_proportions.c:260
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff81777ce0-ffffffff81777db7: __fprop_add_percpu_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __fprop_add_percpu_max(struct fprop_global *p, struct fprop_local_percpu *pl, int max_frac, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff820209d0)
Location: lib/flex_proportions.c:256
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff820209d0-ffffffff82020aa7: __fprop_add_percpu_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __fprop_add_percpu_max(struct fprop_global *p, struct fprop_local_percpu *pl, int max_frac, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff820a0a10)
Location: lib/flex_proportions.c:256
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff820a0a10-ffffffff820a0acf: __fprop_add_percpu_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __fprop_add_percpu_max(struct fprop_global *p, struct fprop_local_percpu *pl, int max_frac, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff821789f0)
Location: lib/flex_proportions.c:256
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff821789f0-ffffffff82178aaf: __fprop_add_percpu_max (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
