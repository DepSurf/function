# Function: <code>cfq_put_cooperator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cfq_put_cooperator(struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e2b20)
Location: block/cfq-iosched.c:3572
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_set_request
```
**Symbols:**

```
ffffffff813e2b20-ffffffff813e2b73: cfq_put_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cfq_put_cooperator(struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81428d70)
Location: block/cfq-iosched.c:3615
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_exit_cfqq
```
**Symbols:**

```
ffffffff81428d70-ffffffff81428dc3: cfq_put_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cfq_put_cooperator(struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81441200)
Location: block/cfq-iosched.c:3614
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_exit_cfqq
```
**Symbols:**

```
ffffffff81441200-ffffffff81441253: cfq_put_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cfq_put_cooperator(struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814503d0)
Location: block/cfq-iosched.c:3621
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_exit_cfqq
```
**Symbols:**

```
ffffffff814503d0-ffffffff8145041b: cfq_put_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cfq_put_cooperator(struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147e540)
Location: block/cfq-iosched.c:3598
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_exit_cfqq
```
**Symbols:**

```
ffffffff8147e540-ffffffff8147e589: cfq_put_cooperator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cfq_put_cooperator(struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b2510)
Location: block/cfq-iosched.c:3601
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_exit_cfqq
```
**Symbols:**

```
ffffffff814b2510-ffffffff814b2559: cfq_put_cooperator (STB_LOCAL)
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
