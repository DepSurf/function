# Function: <code>blk_mq_alloc_set_map_and_rqs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_set_map_and_rqs(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:4133
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8168b2a0-ffffffff8168b417: blk_mq_alloc_set_map_and_rqs (STB_LOCAL)
ffffffff81e8bd26-ffffffff81e8bd3a: blk_mq_alloc_set_map_and_rqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_alloc_set_map_and_rqs(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817492a0)
Location: block/blk-mq.c:4335
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff817492a0-ffffffff81749424: blk_mq_alloc_set_map_and_rqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_alloc_set_map_and_rqs(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817859e0)
Location: block/blk-mq.c:4334
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff817859e0-ffffffff81785b64: blk_mq_alloc_set_map_and_rqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_alloc_set_map_and_rqs(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c8060)
Location: block/blk-mq.c:4350
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff817c8060-ffffffff817c81e4: blk_mq_alloc_set_map_and_rqs (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
