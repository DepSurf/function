# Function: <code>cfq_del_cfqq_rr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_del_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e0d40)
Location: block/cfq-iosched.c:2372
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:__cfq_slice_expired
```
**Symbols:**

```
ffffffff813e0d40-ffffffff813e0fa4: cfq_del_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_del_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81426f60)
Location: block/cfq-iosched.c:2397
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_merged_requests
```
**Symbols:**

```
ffffffff81426f60-ffffffff814271c4: cfq_del_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_del_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143ee40)
Location: block/cfq-iosched.c:2388
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_merged_requests
```
**Symbols:**

```
ffffffff8143ee40-ffffffff8143efdd: cfq_del_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_del_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144e1c0)
Location: block/cfq-iosched.c:2393
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_merged_requests
```
**Symbols:**

```
ffffffff8144e1c0-ffffffff8144e352: cfq_del_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cfq_del_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147ab10)
Location: block/cfq-iosched.c:2369
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_merged_requests
```
**Symbols:**

```
ffffffff8147ab10-ffffffff8147ac93: cfq_del_cfqq_rr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cfq_del_cfqq_rr(struct cfq_data *cfqd, struct cfq_queue *cfqq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814af4e0)
Location: block/cfq-iosched.c:2372
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_merged_requests
```
**Symbols:**

```
ffffffff814af4e0-ffffffff814af661: cfq_del_cfqq_rr (STB_LOCAL)
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
