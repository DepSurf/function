# Function: <code>cfq_find_next_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct request *cfq_find_next_rq(struct cfq_data *cfqd, struct cfq_queue *cfqq, struct request *last);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813dedb0)
Location: block/cfq-iosched.c:1209
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_dispatch_insert
```
**Symbols:**

```
ffffffff813dedb0-ffffffff813dee63: cfq_find_next_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request *cfq_find_next_rq(struct cfq_data *cfqd, struct cfq_queue *cfqq, struct request *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814249a0)
Location: block/cfq-iosched.c:1232
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff814249a0-ffffffff81424a69: cfq_find_next_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request *cfq_find_next_rq(struct cfq_data *cfqd, struct cfq_queue *cfqq, struct request *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814403b0)
Location: block/cfq-iosched.c:1223
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff814403b0-ffffffff81440479: cfq_find_next_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *cfq_find_next_rq(struct cfq_data *cfqd, struct cfq_queue *cfqq, struct request *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144f650)
Location: block/cfq-iosched.c:1219
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff8144f650-ffffffff8144f71e: cfq_find_next_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *cfq_find_next_rq(struct cfq_data *cfqd, struct cfq_queue *cfqq, struct request *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147b790)
Location: block/cfq-iosched.c:1198
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff8147b790-ffffffff8147b85e: cfq_find_next_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *cfq_find_next_rq(struct cfq_data *cfqd, struct cfq_queue *cfqq, struct request *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814afe90)
Location: block/cfq-iosched.c:1201
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff814afe90-ffffffff814aff4b: cfq_find_next_rq (STB_LOCAL)
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
