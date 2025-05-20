# Function: <code>cfq_group_service_tree_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cfq_group_service_tree_add(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813dd7d0)
Location: block/cfq-iosched.c:1300
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_served
```
**Symbols:**

```
ffffffff813dd7d0-ffffffff813dd918: cfq_group_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cfq_group_service_tree_add(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814238d0)
Location: block/cfq-iosched.c:1323
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_served
```
**Symbols:**

```
ffffffff814238d0-ffffffff81423a12: cfq_group_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cfq_group_service_tree_add(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8143efe0)
Location: block/cfq-iosched.c:1314
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_served
```
**Symbols:**

```
ffffffff8143efe0-ffffffff8143f122: cfq_group_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cfq_group_service_tree_add(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144e360)
Location: block/cfq-iosched.c:1310
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_served
```
**Symbols:**

```
ffffffff8144e360-ffffffff8144e4a0: cfq_group_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cfq_group_service_tree_add(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147a710)
Location: block/cfq-iosched.c:1290
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_service_tree_add
```
**Symbols:**

```
ffffffff8147a710-ffffffff8147a84b: cfq_group_service_tree_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cfq_group_service_tree_add(struct cfq_rb_root *st, struct cfq_group *cfqg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814af0d0)
Location: block/cfq-iosched.c:1293
Inline: False
Direct callers:
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_service_tree_add
```
**Symbols:**

```
ffffffff814af0d0-ffffffff814af227: cfq_group_service_tree_add (STB_LOCAL)
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
