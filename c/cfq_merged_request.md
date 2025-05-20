# Function: <code>cfq_merged_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cfq_merged_request(struct request_queue *q, struct request *req, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e0660)
Location: block/cfq-iosched.c:2530
Inline: True
```
**Symbols:**

```
ffffffff813e0660-ffffffff813e075d: cfq_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cfq_merged_request(struct request_queue *q, struct request *req, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81426680)
Location: block/cfq-iosched.c:2555
Inline: True
```
**Symbols:**

```
ffffffff81426680-ffffffff81426799: cfq_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cfq_merged_request(struct request_queue *q, struct request *req, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814442e0)
Location: block/cfq-iosched.c:2546
Inline: True
```
**Symbols:**

```
ffffffff814442e0-ffffffff814443f7: cfq_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cfq_merged_request(struct request_queue *q, struct request *req, enum elv_merge type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81453410)
Location: block/cfq-iosched.c:2551
Inline: True
```
**Symbols:**

```
ffffffff81453410-ffffffff8145352e: cfq_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cfq_merged_request(struct request_queue *q, struct request *req, enum elv_merge type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147cd30)
Location: block/cfq-iosched.c:2527
Inline: True
```
**Symbols:**

```
ffffffff8147cd30-ffffffff8147ce4e: cfq_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cfq_merged_request(struct request_queue *q, struct request *req, enum elv_merge type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b1740)
Location: block/cfq-iosched.c:2530
Inline: True
```
**Symbols:**

```
ffffffff814b1740-ffffffff814b1866: cfq_merged_request (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int type</code> ➡️ <code>enum elv_merge type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
