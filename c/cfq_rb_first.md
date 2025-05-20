# Function: <code>cfq_rb_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cfq_queue *cfq_rb_first(struct cfq_rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813dd9e0)
Location: block/cfq-iosched.c:1165
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff813dd9e0-ffffffff813dda1e: cfq_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cfq_queue *cfq_rb_first(struct cfq_rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81423ae0)
Location: block/cfq-iosched.c:1188
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_service_tree_add
```
**Symbols:**

```
ffffffff81423ae0-ffffffff81423b1e: cfq_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cfq_queue *cfq_rb_first(struct cfq_rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143f520)
Location: block/cfq-iosched.c:1179
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_service_tree_add
```
**Symbols:**

```
ffffffff8143f520-ffffffff8143f55e: cfq_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cfq_queue *cfq_rb_first(struct cfq_rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144e7b0)
Location: block/cfq-iosched.c:1175
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_service_tree_add
```
**Symbols:**

```
ffffffff8144e7b0-ffffffff8144e7ee: cfq_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147ed74)
Location: block/cfq-iosched.c:1169
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_service_tree_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b31bf)
Location: block/cfq-iosched.c:1172
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_service_tree_add
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
</ul>
