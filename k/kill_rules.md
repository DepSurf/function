# Function: <code>kill_rules</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kill_rules(struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8112ab20)
Location: kernel/audit_tree.c:470
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
ffffffff8112ab20-ffffffff8112acb3: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kill_rules(struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81132d10)
Location: kernel/audit_tree.c:470
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
ffffffff81132d10-ffffffff81132e9a: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kill_rules(struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113ca60)
Location: kernel/audit_tree.c:479
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
ffffffff8113ca60-ffffffff8113cbd6: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kill_rules(struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113e0f0)
Location: kernel/audit_tree.c:510
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
ffffffff8113e0f0-ffffffff8113e263: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kill_rules(struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8114aef0)
Location: kernel/audit_tree.c:511
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
ffffffff8114aef0-ffffffff8114b063: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kill_rules(struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81159950)
Location: kernel/audit_tree.c:511
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81159950-ffffffff81159ac3: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kill_rules(struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81166890)
Location: kernel/audit_tree.c:543
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81166890-ffffffff811669fe: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81173440)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81173440-ffffffff811735c0: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8117f2b0)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff8117f2b0-ffffffff8117f430: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811927e0)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff811927e0-ffffffff81192960: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8118f930)
Location: kernel/audit_tree.c:542
Inline: False
Direct callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff8118f930-ffffffff8118fab0: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81190870)
Location: kernel/audit_tree.c:542
Inline: False
Direct callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81190870-ffffffff811909f0: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811b9750)
Location: kernel/audit_tree.c:542
Inline: False
Direct callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff811b9750-ffffffff811b98d0: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811ec860)
Location: kernel/audit_tree.c:542
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff811ec860-ffffffff811ec9ed: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81232d90)
Location: kernel/audit_tree.c:542
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81232d90-ffffffff81232f1d: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81249a10)
Location: kernel/audit_tree.c:542
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81249a10-ffffffff81249b9d: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81263920)
Location: kernel/audit_tree.c:542
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81263920-ffffffff81263aad: kill_rules (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffff8000101f4298)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
ffff8000101f4298-ffff8000101f43ec: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c043462c)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
c043462c-c0434784: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c000000000269580)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
```
**Symbols:**

```
c000000000269580-c000000000269778: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffe000167566)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffe000167566-ffffffe0001676bc: kill_rules (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811778d0)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff811778d0-ffffffff81177a50: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8116aa70)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff8116aa70-ffffffff8116abf0: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811756a0)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff811756a0-ffffffff81175820: kill_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kill_rules(struct audit_context *context, struct audit_tree *tree);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81182f80)
Location: kernel/audit_tree.c:544
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:trim_marked
```
**Symbols:**

```
ffffffff81182f80-ffffffff81183100: kill_rules (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct audit_context *context</code>
</li>
<li>
<b>Param reordered. </b>
<code>tree</code> ➡️ <code>context, tree</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
