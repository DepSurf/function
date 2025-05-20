# Function: <code>cfq_group_service_tree_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_group_service_tree_del(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813dd6b0)
Location: block/cfq-iosched.c:1376
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_group_served
```
**Symbols:**

```
ffffffff813dd6b0-ffffffff813dd7c3: cfq_group_service_tree_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_group_service_tree_del(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814237b0)
Location: block/cfq-iosched.c:1399
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
```
**Symbols:**

```
ffffffff814237b0-ffffffff814238cd: cfq_group_service_tree_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_group_service_tree_del(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143ec50)
Location: block/cfq-iosched.c:1390
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
```
**Symbols:**

```
ffffffff8143ec50-ffffffff8143ed6d: cfq_group_service_tree_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_group_service_tree_del(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144e020)
Location: block/cfq-iosched.c:1395
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
```
**Symbols:**

```
ffffffff8144e020-ffffffff8144e0f0: cfq_group_service_tree_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cfq_group_service_tree_del(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147a660)
Location: block/cfq-iosched.c:1375
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_del_cfqq_rr
```
**Symbols:**

```
ffffffff8147a660-ffffffff8147a707: cfq_group_service_tree_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cfq_group_service_tree_del(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814af010)
Location: block/cfq-iosched.c:1378
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_del_cfqq_rr
```
**Symbols:**

```
ffffffff814af010-ffffffff814af0cc: cfq_group_service_tree_del (STB_LOCAL)
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
