# Function: <code>untag_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void untag_chunk(struct node *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8112b4d0)
Location: kernel/audit_tree.c:218
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_one
```
**Symbols:**

```
ffffffff8112b4d0-ffffffff8112b903: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void untag_chunk(struct node *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811336e0)
Location: kernel/audit_tree.c:218
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_one
```
**Symbols:**

```
ffffffff811336e0-ffffffff81133af6: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void untag_chunk(struct node *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113d430)
Location: kernel/audit_tree.c:218
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_one
```
**Symbols:**

```
ffffffff8113d430-ffffffff8113d874: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void untag_chunk(struct node *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113ea50)
Location: kernel/audit_tree.c:240
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_one
```
**Symbols:**

```
ffffffff8113ea50-ffffffff8113eeb4: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void untag_chunk(struct node *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8114b860)
Location: kernel/audit_tree.c:241
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_one
```
**Symbols:**

```
ffffffff8114b860-ffffffff8114bccc: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void untag_chunk(struct node *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81159d60)
Location: kernel/audit_tree.c:241
Inline: False
Direct callers:
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_one
```
**Symbols:**

```
ffffffff81159d60-ffffffff8115a1df: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81166efe)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81173afe)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8117f96e)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void untag_chunk(struct audit_chunk *chunk, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811931e0)
Location: kernel/audit_tree.c:351
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
**Symbols:**

```
ffffffff811931e0-ffffffff8119335e: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void untag_chunk(struct audit_chunk *chunk, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81190350)
Location: kernel/audit_tree.c:349
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
**Symbols:**

```
ffffffff81190350-ffffffff811904ce: untag_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811910ad)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811b9f8d)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811ed131)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff812336d1)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8124a3c1)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff812642d1)
Location: kernel/audit_tree.c:349
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffff8000101f4780)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c0434d48)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c000000000269e20)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffe000167a38)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81177f8e)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8116b12e)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81175d5e)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8118364c)
Location: kernel/audit_tree.c:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
</details>
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
