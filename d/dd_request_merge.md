# Function: <code>dd_request_merge</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814c81c0)
Location: block/mq-deadline.c:448
Inline: True
```
**Symbols:**

```
ffffffff814c81c0-ffffffff814c8240: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814f6a70)
Location: block/mq-deadline.c:449
Inline: True
```
**Symbols:**

```
ffffffff814f6a70-ffffffff814f6af0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81514920)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
ffffffff81514920-ffffffff815149a0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81575530)
Location: block/mq-deadline.c:439
Inline: False
```
**Symbols:**

```
ffffffff81575530-ffffffff815755b0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81592340)
Location: block/mq-deadline.c:441
Inline: False
```
**Symbols:**

```
ffffffff81592340-ffffffff815923c0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81599010)
Location: block/mq-deadline.c:441
Inline: False
```
**Symbols:**

```
ffffffff81599010-ffffffff81599097: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81601450)
Location: block/mq-deadline.c:607
Inline: False
```
**Symbols:**

```
ffffffff81601450-ffffffff8160154c: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b3cf0)
Location: block/mq-deadline.c:660
Inline: False
```
**Symbols:**

```
ffffffff816b3cf0-ffffffff816b3df8: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81773430)
Location: block/mq-deadline.c:718
Inline: False
```
**Symbols:**

```
ffffffff81773430-ffffffff81773536: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817b22d0)
Location: block/mq-deadline.c:743
Inline: False
```
**Symbols:**

```
ffffffff817b22d0-ffffffff817b23d6: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817f60e0)
Location: block/mq-deadline.c:743
Inline: False
```
**Symbols:**

```
ffffffff817f60e0-ffffffff817f61e6: dd_request_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffff800010619160)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
ffff800010619160-ffff80001061920c: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c07c4104)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
c07c4104-c07c41a0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c0000000007b8a20)
Location: block/mq-deadline.c:439
Inline: False
```
**Symbols:**

```
c0000000007b8a20-c0000000007b8afc: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffe00044f328)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
ffffffe00044f328-ffffffe00044f3b0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8150cf00)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
ffffffff8150cf00-ffffffff8150cf80: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814fd330)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
ffffffff814fd330-ffffffff814fd3b0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81508f90)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
ffffffff81508f90-ffffffff81509010: dd_request_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dd_request_merge(struct request_queue *q, struct request **rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81522730)
Location: block/mq-deadline.c:439
Inline: True
```
**Symbols:**

```
ffffffff81522730-ffffffff815227b0: dd_request_merge (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
