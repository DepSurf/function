# Function: <code>cfq_service_tree_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_service_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813dda20)
Location: block/cfq-iosched.c:2199
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_add_cfqq_rr
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_preempt_queue
```
**Symbols:**

```
ffffffff813dda20-ffffffff813ddd4f: cfq_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_service_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81423b20)
Location: block/cfq-iosched.c:2223
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_cfqq_rr
```
**Symbols:**

```
ffffffff81423b20-ffffffff81423e51: cfq_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_service_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143f560)
Location: block/cfq-iosched.c:2214
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_cfqq_rr
```
**Symbols:**

```
ffffffff8143f560-ffffffff8143f889: cfq_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_service_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144e7f0)
Location: block/cfq-iosched.c:2219
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_cfqq_rr
```
**Symbols:**

```
ffffffff8144e7f0-ffffffff8144eae1: cfq_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cfq_service_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147a850)
Location: block/cfq-iosched.c:2199
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff8147a850-ffffffff8147ab02: cfq_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cfq_service_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814af230)
Location: block/cfq-iosched.c:2202
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff814af230-ffffffff814af4da: cfq_service_tree_add (STB_LOCAL)
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
