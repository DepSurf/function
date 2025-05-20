# Function: <code>cfq_prio_tree_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_prio_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813dd920)
Location: block/cfq-iosched.c:2313
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_add_cfqq_rr
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff813dd920-ffffffff813dd9d4: cfq_prio_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_prio_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81423a20)
Location: block/cfq-iosched.c:2338
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_add_cfqq_rr
```
**Symbols:**

```
ffffffff81423a20-ffffffff81423ad4: cfq_prio_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_prio_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143f130)
Location: block/cfq-iosched.c:2329
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_add_cfqq_rr
```
**Symbols:**

```
ffffffff8143f130-ffffffff8143f1e4: cfq_prio_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cfq_prio_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144f8f0)
Location: block/cfq-iosched.c:2334
Inline: True
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_add_cfqq_rr
```
**Symbols:**

```
ffffffff8144f8f0-ffffffff8144f9a4: cfq_prio_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cfq_prio_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147b870)
Location: block/cfq-iosched.c:2310
Inline: True
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff8147b870-ffffffff8147b924: cfq_prio_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cfq_prio_tree_add(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814af670)
Location: block/cfq-iosched.c:2313
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff814af670-ffffffff814af729: cfq_prio_tree_add (STB_LOCAL)
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
