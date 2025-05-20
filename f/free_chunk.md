# Function: <code>free_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8112af40)
Location: kernel/audit_tree.c:109
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:audit_put_chunk
```
**Symbols:**

```
ffffffff8112af40-ffffffff8112af98: free_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81133140)
Location: kernel/audit_tree.c:109
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:audit_put_chunk
```
**Symbols:**

```
ffffffff81133140-ffffffff81133196: free_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113ce80)
Location: kernel/audit_tree.c:109
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:audit_put_chunk
```
**Symbols:**

```
ffffffff8113ce80-ffffffff8113ced6: free_chunk (STB_LOCAL)
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
In kernel/audit_tree.c (ffffffff8113f155)
Location: kernel/audit_tree.c:110
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (ffffffff8114bf78)
Location: kernel/audit_tree.c:111
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:111
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (ffff8000101f5544)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (c04356c4)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_chunk(struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffe000167918)
Location: kernel/audit_tree.c:128
Inline: False
Direct callers:
  - kernel/audit_tree.c:__put_chunk
```
**Symbols:**

```
ffffffe000167918-ffffffe000167996: free_chunk (STB_LOCAL)
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
In kernel/audit_tree.c (0)
Location: kernel/audit_tree.c:128
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
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
</ul>
<b>Arch</b>
<ul>
</ul>
