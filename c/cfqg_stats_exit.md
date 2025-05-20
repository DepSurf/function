# Function: <code>cfqg_stats_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfqg_stats_exit(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813ddfe0)
Location: block/cfq-iosched.c:1528
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_free
  - block/cfq-iosched.c:cfq_pd_alloc
```
**Symbols:**

```
ffffffff813ddfe0-ffffffff813de0ac: cfqg_stats_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfqg_stats_exit(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81424120)
Location: block/cfq-iosched.c:1552
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_free
  - block/cfq-iosched.c:cfq_pd_alloc
```
**Symbols:**

```
ffffffff81424120-ffffffff814241c3: cfqg_stats_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfqg_stats_exit(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143fb30)
Location: block/cfq-iosched.c:1543
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_free
  - block/cfq-iosched.c:cfq_pd_alloc
```
**Symbols:**

```
ffffffff8143fb30-ffffffff8143fbd3: cfqg_stats_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfqg_stats_exit(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144ed90)
Location: block/cfq-iosched.c:1548
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_free
  - block/cfq-iosched.c:cfq_pd_alloc
```
**Symbols:**

```
ffffffff8144ed90-ffffffff8144ee5c: cfqg_stats_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cfqg_stats_exit(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147aed0)
Location: block/cfq-iosched.c:1528
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_free
  - block/cfq-iosched.c:cfq_pd_alloc
```
**Symbols:**

```
ffffffff8147aed0-ffffffff8147af9c: cfqg_stats_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cfqg_stats_exit(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b03e0)
Location: block/cfq-iosched.c:1531
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_pd_free
  - block/cfq-iosched.c:cfq_pd_alloc
```
**Symbols:**

```
ffffffff814b03e0-ffffffff814b04ac: cfqg_stats_exit (STB_LOCAL)
```
</details>
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
</ul>
