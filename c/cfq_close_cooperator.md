# Function: <code>cfq_close_cooperator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cfq_queue *cfq_close_cooperator(struct cfq_data *cfqd, struct cfq_queue *cur_cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813dec20)
Location: block/cfq-iosched.c:2814
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_completed_request
```
**Symbols:**

```
ffffffff813dec20-ffffffff813dedaa: cfq_close_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cfq_queue *cfq_close_cooperator(struct cfq_data *cfqd, struct cfq_queue *cur_cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81424ca0)
Location: block/cfq-iosched.c:2845
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff81424ca0-ffffffff81424e3a: cfq_close_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cfq_queue *cfq_close_cooperator(struct cfq_data *cfqd, struct cfq_queue *cur_cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81441260)
Location: block/cfq-iosched.c:2837
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff81441260-ffffffff814413fa: cfq_close_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cfq_queue *cfq_close_cooperator(struct cfq_data *cfqd, struct cfq_queue *cur_cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81450530)
Location: block/cfq-iosched.c:2844
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff81450530-ffffffff814506d4: cfq_close_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cfq_queue *cfq_close_cooperator(struct cfq_data *cfqd, struct cfq_queue *cur_cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147bb50)
Location: block/cfq-iosched.c:2820
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff8147bb50-ffffffff8147bcf4: cfq_close_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cfq_queue *cfq_close_cooperator(struct cfq_data *cfqd, struct cfq_queue *cur_cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b0190)
Location: block/cfq-iosched.c:2823
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff814b0190-ffffffff814b02f5: cfq_close_cooperator (STB_LOCAL)
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
