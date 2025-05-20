# Function: <code>cfq_arm_slice_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_arm_slice_timer(struct cfq_data *cfqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e4900)
Location: block/cfq-iosched.c:2897
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
```
**Symbols:**

```
ffffffff813e4900-ffffffff813e4c43: cfq_arm_slice_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_arm_slice_timer(struct cfq_data *cfqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8142ab80)
Location: block/cfq-iosched.c:2928
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
```
**Symbols:**

```
ffffffff8142ab80-ffffffff8142aefc: cfq_arm_slice_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_arm_slice_timer(struct cfq_data *cfqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81441b60)
Location: block/cfq-iosched.c:2920
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
```
**Symbols:**

```
ffffffff81441b60-ffffffff81441e5d: cfq_arm_slice_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_arm_slice_timer(struct cfq_data *cfqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81450e30)
Location: block/cfq-iosched.c:2927
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
```
**Symbols:**

```
ffffffff81450e30-ffffffff814510f6: cfq_arm_slice_timer (STB_LOCAL)
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
In block/cfq-iosched.c (ffffffff8147fb33)
Location: block/cfq-iosched.c:2903
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
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
In block/cfq-iosched.c (ffffffff814b48ec)
Location: block/cfq-iosched.c:2906
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
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
