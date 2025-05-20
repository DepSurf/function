# Function: <code>cfq_preempt_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_preempt_queue(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e21e0)
Location: block/cfq-iosched.c:3997
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff813e21e0-ffffffff813e241e: cfq_preempt_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_preempt_queue(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81428410)
Location: block/cfq-iosched.c:4047
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff81428410-ffffffff8142864b: cfq_preempt_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_preempt_queue(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81440a40)
Location: block/cfq-iosched.c:4059
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff81440a40-ffffffff81440bb7: cfq_preempt_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_preempt_queue(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144fd60)
Location: block/cfq-iosched.c:4064
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_insert_request
```
**Symbols:**

```
ffffffff8144fd60-ffffffff8144feca: cfq_preempt_queue (STB_LOCAL)
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
In block/cfq-iosched.c (ffffffff8147de12)
Location: block/cfq-iosched.c:4041
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
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
In block/cfq-iosched.c (ffffffff814b3ce3)
Location: block/cfq-iosched.c:4044
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
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
