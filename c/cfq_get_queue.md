# Function: <code>cfq_get_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cfq_queue *cfq_get_queue(struct cfq_data *cfqd, bool is_sync, struct cfq_io_cq *cic, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e1800)
Location: block/cfq-iosched.c:3778
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
```
**Symbols:**

```
ffffffff813e1800-ffffffff813e1c5c: cfq_get_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cfq_queue *cfq_get_queue(struct cfq_data *cfqd, bool is_sync, struct cfq_io_cq *cic, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81427a30)
Location: block/cfq-iosched.c:3822
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
```
**Symbols:**

```
ffffffff81427a30-ffffffff81427e89: cfq_get_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cfq_queue *cfq_get_queue(struct cfq_data *cfqd, bool is_sync, struct cfq_io_cq *cic, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81441630)
Location: block/cfq-iosched.c:3827
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
```
**Symbols:**

```
ffffffff81441630-ffffffff814419c3: cfq_get_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cfq_queue *cfq_get_queue(struct cfq_data *cfqd, bool is_sync, struct cfq_io_cq *cic, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81450920)
Location: block/cfq-iosched.c:3830
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
```
**Symbols:**

```
ffffffff81450920-ffffffff81450c92: cfq_get_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cfq_queue *cfq_get_queue(struct cfq_data *cfqd, bool is_sync, struct cfq_io_cq *cic, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147bf40)
Location: block/cfq-iosched.c:3807
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
```
**Symbols:**

```
ffffffff8147bf40-ffffffff8147c266: cfq_get_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cfq_queue *cfq_get_queue(struct cfq_data *cfqd, bool is_sync, struct cfq_io_cq *cic, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b1030)
Location: block/cfq-iosched.c:3810
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
```
**Symbols:**

```
ffffffff814b1030-ffffffff814b1368: cfq_get_queue (STB_LOCAL)
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
