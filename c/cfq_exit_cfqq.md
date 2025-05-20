# Function: <code>cfq_exit_cfqq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_exit_cfqq(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e2c90)
Location: block/cfq-iosched.c:3593
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_icq
  - block/cfq-iosched.c:cfq_exit_icq
```
**Symbols:**

```
ffffffff813e2c90-ffffffff813e2d00: cfq_exit_cfqq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_exit_cfqq(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81428ee0)
Location: block/cfq-iosched.c:3636
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_icq
  - block/cfq-iosched.c:cfq_exit_icq
```
**Symbols:**

```
ffffffff81428ee0-ffffffff81428f50: cfq_exit_cfqq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_exit_cfqq(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81442740)
Location: block/cfq-iosched.c:3635
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_icq
  - block/cfq-iosched.c:cfq_exit_icq
```
**Symbols:**

```
ffffffff81442740-ffffffff814427b0: cfq_exit_cfqq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_exit_cfqq(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814519b0)
Location: block/cfq-iosched.c:3642
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_icq
  - block/cfq-iosched.c:cfq_exit_icq
```
**Symbols:**

```
ffffffff814519b0-ffffffff81451a20: cfq_exit_cfqq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cfq_exit_cfqq(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147eb70)
Location: block/cfq-iosched.c:3619
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_icq
  - block/cfq-iosched.c:cfq_exit_icq
```
**Symbols:**

```
ffffffff8147eb70-ffffffff8147ebe2: cfq_exit_cfqq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cfq_exit_cfqq(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b2c90)
Location: block/cfq-iosched.c:3622
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_icq
  - block/cfq-iosched.c:cfq_exit_icq
```
**Symbols:**

```
ffffffff814b2c90-ffffffff814b2d02: cfq_exit_cfqq (STB_LOCAL)
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
