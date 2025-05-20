# Function: <code>frag_show_print</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811acb90)
Location: mm/vmstat.c:935
Inline: False
```
**Symbols:**

```
ffffffff811acb90-ffffffff811acbfb: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c5bb0)
Location: mm/vmstat.c:1142
Inline: False
```
**Symbols:**

```
ffffffff811c5bb0-ffffffff811c5c22: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5ca0)
Location: mm/vmstat.c:1142
Inline: False
```
**Symbols:**

```
ffffffff811d5ca0-ffffffff811d5d12: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811de9e0)
Location: mm/vmstat.c:1154
Inline: False
```
**Symbols:**

```
ffffffff811de9e0-ffffffff811dea52: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f45b0)
Location: mm/vmstat.c:1348
Inline: False
```
**Symbols:**

```
ffffffff811f45b0-ffffffff811f4622: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81215810)
Location: mm/vmstat.c:1349
Inline: False
```
**Symbols:**

```
ffffffff81215810-ffffffff81215882: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81228700)
Location: mm/vmstat.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81228700-ffffffff81228772: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81238410)
Location: mm/vmstat.c:1349
Inline: False
```
**Symbols:**

```
ffffffff81238410-ffffffff8123847b: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81246700)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
ffffffff81246700-ffffffff8124676b: frag_show_print (STB_LOCAL)
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
In mm/vmstat.c (ffffffff8127507c)
Location: mm/vmstat.c:1363
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff8127f7ec)
Location: mm/vmstat.c:1410
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff81284a3c)
Location: mm/vmstat.c:1433
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff812c2ee0)
Location: mm/vmstat.c:1441
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff813201aa)
Location: mm/vmstat.c:1464
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff81393eba)
Location: mm/vmstat.c:1459
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff813c69ba)
Location: mm/vmstat.c:1469
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff813f133a)
Location: mm/vmstat.c:1473
Inline: True
Inline callers:
  - mm/vmstat.c:frag_show
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
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102d9988)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
ffff8000102d9988-ffff8000102d9a0c: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0500bf0)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
c0500bf0-c0500c58: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c000000000399f30)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
c000000000399f30-c000000000399fe0: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f3fba)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
ffffffe0001f3fba-ffffffe0001f403a: frag_show_print (STB_LOCAL)
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
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123ed50)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
ffffffff8123ed50-ffffffff8123edbb: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81231d50)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
ffffffff81231d50-ffffffff81231dbb: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123caf0)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
ffffffff8123caf0-ffffffff8123cb5b: frag_show_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void frag_show_print(struct seq_file *m, pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124c220)
Location: mm/vmstat.c:1351
Inline: False
```
**Symbols:**

```
ffffffff8124c220-ffffffff8124c28b: frag_show_print (STB_LOCAL)
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
