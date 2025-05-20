# Function: <code>prune_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void prune_one(struct audit_tree *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8112b910)
Location: kernel/audit_tree.c:495
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
ffffffff8112b910-ffffffff8112b971: prune_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void prune_one(struct audit_tree *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81133b00)
Location: kernel/audit_tree.c:495
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81133b00-ffffffff81133b60: prune_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void prune_one(struct audit_tree *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113d880)
Location: kernel/audit_tree.c:504
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8113d880-ffffffff8113d8e0: prune_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void prune_one(struct audit_tree *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113eec0)
Location: kernel/audit_tree.c:535
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8113eec0-ffffffff8113ef20: prune_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void prune_one(struct audit_tree *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8114bcd0)
Location: kernel/audit_tree.c:536
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8114bcd0-ffffffff8114bd36: prune_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void prune_one(struct audit_tree *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8115a1e0)
Location: kernel/audit_tree.c:536
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff8115a1e0-ffffffff8115a24b: prune_one (STB_LOCAL)
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
In kernel/audit_tree.c (ffffffff81168461)
Location: kernel/audit_tree.c:603
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff811750d9)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff81180f49)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff811948c9)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff81191a39)
Location: kernel/audit_tree.c:602
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff811929ab)
Location: kernel/audit_tree.c:601
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff811bb83b)
Location: kernel/audit_tree.c:601
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff811eec8b)
Location: kernel/audit_tree.c:601
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff8123535b)
Location: kernel/audit_tree.c:601
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff8124c038)
Location: kernel/audit_tree.c:601
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff81265f38)
Location: kernel/audit_tree.c:601
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffff8000101f64b0)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
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
In kernel/audit_tree.c (c043647c)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
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
In kernel/audit_tree.c (c00000000026c078)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
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
In kernel/audit_tree.c (ffffffe0001694d4)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff81179569)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff8116c709)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff81177339)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
In kernel/audit_tree.c (ffffffff81184c09)
Location: kernel/audit_tree.c:604
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:trim_marked
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
</ul>
