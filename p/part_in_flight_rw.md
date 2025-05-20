# Function: <code>part_in_flight_rw</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81497fa0)
Location: block/genhd.c:85
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff81497fa0-ffffffff81497fcc: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b2030)
Location: block/genhd.c:88
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff814b2030-ffffffff814b20ef: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0480)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff814e0480-ffffffff814e0538: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f98b0)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff814f98b0-ffffffff814f9968: part_in_flight_rw (STB_GLOBAL)
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
In block/genhd.c (ffffffff815597b5)
Location: block/genhd.c:131
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
In block/genhd.c (ffffffff81575db5)
Location: block/genhd.c:148
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
In block/genhd.c (ffffffff8157dbf9)
Location: block/genhd.c:145
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
In block/genhd.c (ffffffff815e347b)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
In block/genhd.c (ffffffff8169270e)
Location: block/genhd.c:163
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
In block/genhd.c (ffffffff81750da3)
Location: block/genhd.c:140
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
In block/genhd.c (ffffffff8178d376)
Location: block/genhd.c:136
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
In block/genhd.c (ffffffff817cfbd6)
Location: block/genhd.c:136
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
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
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fb260)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffff8000105fb260-ffff8000105fb36c: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a637c)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
c07a637c-c07a6440: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c0000000007943a0)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
c0000000007943a0-c000000000794508: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe00043747c)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffe00043747c-ffffffe000437546: part_in_flight_rw (STB_GLOBAL)
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
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f1e90)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff814f1e90-ffffffff814f1f48: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e23c0)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff814e23c0-ffffffff814e2478: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814edf20)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff814edf20-ffffffff814edfd8: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81506fa0)
Location: block/genhd.c:89
Inline: False
Direct callers:
  - block/partition-generic.c:part_inflight_show
```
**Symbols:**

```
ffffffff81506fa0-ffffffff81507058: part_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
