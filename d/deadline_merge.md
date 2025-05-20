# Function: <code>deadline_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int deadline_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff813dcb40)
Location: block/deadline-iosched.c:125
Inline: True
```
**Symbols:**

```
ffffffff813dcb40-ffffffff813dcbc1: deadline_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int deadline_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff81422790)
Location: block/deadline-iosched.c:124
Inline: True
```
**Symbols:**

```
ffffffff81422790-ffffffff81422818: deadline_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int deadline_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff8143d8c0)
Location: block/deadline-iosched.c:124
Inline: True
```
**Symbols:**

```
ffffffff8143d8c0-ffffffff8143d940: deadline_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge deadline_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff8144cce0)
Location: block/deadline-iosched.c:124
Inline: True
```
**Symbols:**

```
ffffffff8144cce0-ffffffff8144cd60: deadline_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge deadline_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814793e0)
Location: block/deadline-iosched.c:124
Inline: True
```
**Symbols:**

```
ffffffff814793e0-ffffffff81479460: deadline_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum elv_merge deadline_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814ada50)
Location: block/deadline-iosched.c:128
Inline: True
```
**Symbols:**

```
ffffffff814ada50-ffffffff814adac9: deadline_merge (STB_LOCAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum elv_merge</code>
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
