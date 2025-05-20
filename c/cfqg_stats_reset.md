# Function: <code>cfqg_stats_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfqg_stats_reset(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813ddef0)
Location: block/cfq-iosched.c:703
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_reset_stats
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff813ddef0-ffffffff813ddfb1: cfqg_stats_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfqg_stats_reset(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81424030)
Location: block/cfq-iosched.c:715
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_reset_stats
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff81424030-ffffffff814240f4: cfqg_stats_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfqg_stats_reset(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143fa40)
Location: block/cfq-iosched.c:715
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_reset_stats
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff8143fa40-ffffffff8143fb04: cfqg_stats_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfqg_stats_reset(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144eca0)
Location: block/cfq-iosched.c:720
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_reset_stats
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff8144eca0-ffffffff8144ed64: cfqg_stats_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cfqg_stats_reset(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147ade0)
Location: block/cfq-iosched.c:718
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_pd_reset_stats
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff8147ade0-ffffffff8147aea4: cfqg_stats_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cfqg_stats_reset(struct cfqg_stats *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b0300)
Location: block/cfq-iosched.c:720
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_pd_reset_stats
  - block/cfq-iosched.c:cfq_pd_offline
```
**Symbols:**

```
ffffffff814b0300-ffffffff814b03c0: cfqg_stats_reset (STB_LOCAL)
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
