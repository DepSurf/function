# Function: <code>alloc_tree</code>

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
In kernel/audit_tree.c (ffffffff8112c00b)
Location: kernel/audit_tree.c:74
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff811341eb)
Location: kernel/audit_tree.c:74
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff8113df6b)
Location: kernel/audit_tree.c:74
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff8113f60b)
Location: kernel/audit_tree.c:75
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff8114c44b)
Location: kernel/audit_tree.c:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff8115ae9d)
Location: kernel/audit_tree.c:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff81167bfd)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff8117483c)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff811806ac)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81192960)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff81192960-ffffffff811929f2: alloc_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8118fab0)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff8118fab0-ffffffff8118fb42: alloc_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811909f0)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff811909f0-ffffffff81190a82: alloc_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811b98d0)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff811b98d0-ffffffff811b9962: alloc_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811ec9f0)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff811ec9f0-ffffffff811eca7b: alloc_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81232f30)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff81232f30-ffffffff81232fbb: alloc_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81249bb0)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff81249bb0-ffffffff81249c6d: alloc_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_tree *alloc_tree(const char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81263ac0)
Location: kernel/audit_tree.c:93
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_make_tree
```
**Symbols:**

```
ffffffff81263ac0-ffffffff81263b7d: alloc_tree (STB_LOCAL)
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
In kernel/audit_tree.c (ffff8000101f5b20)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (c0435bb0)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (c00000000026b254)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffe000168c76)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff81178ccc)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff8116be6c)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff81176a9c)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
In kernel/audit_tree.c (ffffffff8118437c)
Location: kernel/audit_tree.c:93
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
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
