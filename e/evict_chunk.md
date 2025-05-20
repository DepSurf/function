# Function: <code>evict_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8112acd9)
Location: kernel/audit_tree.c:911
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81132eb9)
Location: kernel/audit_tree.c:909
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113cbf9)
Location: kernel/audit_tree.c:918
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113e289)
Location: kernel/audit_tree.c:951
Inline: True
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
In kernel/audit_tree.c (ffffffff8114b089)
Location: kernel/audit_tree.c:952
Inline: True
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
In kernel/audit_tree.c (ffffffff81159b75)
Location: kernel/audit_tree.c:952
Inline: True
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
In kernel/audit_tree.c (ffffffff81166c83)
Location: kernel/audit_tree.c:1003
Inline: True
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
In kernel/audit_tree.c (ffffffff81173800)
Location: kernel/audit_tree.c:1006
Inline: True
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
In kernel/audit_tree.c (ffffffff8117f670)
Location: kernel/audit_tree.c:1006
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void evict_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81192cd0)
Location: kernel/audit_tree.c:1006
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
**Symbols:**

```
ffffffff81192cd0-ffffffff81192ea0: evict_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void evict_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8118fe40)
Location: kernel/audit_tree.c:1004
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
**Symbols:**

```
ffffffff8118fe40-ffffffff81190010: evict_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void evict_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81190d70)
Location: kernel/audit_tree.c:1004
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
**Symbols:**

```
ffffffff81190d70-ffffffff81190f40: evict_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void evict_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811b9c50)
Location: kernel/audit_tree.c:1000
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
**Symbols:**

```
ffffffff811b9c50-ffffffff811b9e20: evict_chunk (STB_LOCAL)
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
In kernel/audit_tree.c (ffffffff811ece6c)
Location: kernel/audit_tree.c:1001
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
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
In kernel/audit_tree.c (ffffffff812333fc)
Location: kernel/audit_tree.c:1001
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
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
In kernel/audit_tree.c (ffffffff8124a0a9)
Location: kernel/audit_tree.c:1001
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
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
In kernel/audit_tree.c (ffffffff81263fb9)
Location: kernel/audit_tree.c:1001
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
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
In kernel/audit_tree.c (ffff8000101f4d78)
Location: kernel/audit_tree.c:1006
Inline: True
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
In kernel/audit_tree.c (c0434a20)
Location: kernel/audit_tree.c:1006
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
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
In kernel/audit_tree.c (c00000000026989c)
Location: kernel/audit_tree.c:1006
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
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
In kernel/audit_tree.c (ffffffe000167e9a)
Location: kernel/audit_tree.c:1006
Inline: True
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
In kernel/audit_tree.c (ffffffff81177c90)
Location: kernel/audit_tree.c:1006
Inline: True
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
In kernel/audit_tree.c (ffffffff8116ae30)
Location: kernel/audit_tree.c:1006
Inline: True
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
In kernel/audit_tree.c (ffffffff81175a60)
Location: kernel/audit_tree.c:1006
Inline: True
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
In kernel/audit_tree.c (ffffffff8118321a)
Location: kernel/audit_tree.c:1006
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
