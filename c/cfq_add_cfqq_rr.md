# Function: <code>cfq_add_cfqq_rr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_add_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e03c0)
Location: block/cfq-iosched.c:2356
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff813e03c0-ffffffff813e05b1: cfq_add_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_add_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814263b0)
Location: block/cfq-iosched.c:2381
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff814263b0-ffffffff814265a1: cfq_add_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_add_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81441e60)
Location: block/cfq-iosched.c:2372
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff81441e60-ffffffff81441f86: cfq_add_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_add_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814512f0)
Location: block/cfq-iosched.c:2377
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff814512f0-ffffffff8145140b: cfq_add_cfqq_rr (STB_LOCAL)
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
In block/cfq-iosched.c (ffffffff8147c449)
Location: block/cfq-iosched.c:2353
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_add_rq_rb
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
In block/cfq-iosched.c (ffffffff814b0a99)
Location: block/cfq-iosched.c:2356
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_add_rq_rb
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
