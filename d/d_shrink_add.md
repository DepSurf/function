# Function: <code>d_shrink_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812228c0)
Location: fs/dcache.c:414
Inline: False
Direct callers:
  - fs/dcache.c:select_collect
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812228c0-ffffffff81222931: d_shrink_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124a550)
Location: fs/dcache.c:385
Inline: False
Direct callers:
  - fs/dcache.c:select_collect
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff8124a550-ffffffff8124a5c1: d_shrink_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125d4d0)
Location: fs/dcache.c:385
Inline: False
Direct callers:
  - fs/dcache.c:select_collect
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff8125d4d0-ffffffff8125d541: d_shrink_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126ad20)
Location: fs/dcache.c:417
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff8126ad20-ffffffff8126ad64: d_shrink_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128d5a0)
Location: fs/dcache.c:417
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff8128d5a0-ffffffff8128d5e4: d_shrink_add (STB_LOCAL)
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
In fs/dcache.c (ffffffff812b4702)
Location: fs/dcache.c:416
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
In fs/dcache.c (ffffffff812c9982)
Location: fs/dcache.c:425
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e5e00)
Location: fs/dcache.c:425
Inline: False
```
**Symbols:**

```
ffffffff812e5e00-ffffffff812e5e44: d_shrink_add (STB_LOCAL)
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
In fs/dcache.c (ffffffff812f7d00)
Location: fs/dcache.c:425
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff81330fc5)
Location: fs/dcache.c:425
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff8133c955)
Location: fs/dcache.c:425
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff81342dd5)
Location: fs/dcache.c:427
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff81390515)
Location: fs/dcache.c:427
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff81412686)
Location: fs/dcache.c:452
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff8149dc9a)
Location: fs/dcache.c:452
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff814d2ce6)
Location: fs/dcache.c:452
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff81503c80)
Location: fs/dcache.c:453
Inline: True
Inline callers:
  - fs/dcache.c:to_shrink_list
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
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a58b0)
Location: fs/dcache.c:425
Inline: False
```
**Symbols:**

```
ffff8000103a58b0-ffff8000103a593c: d_shrink_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0586f90)
Location: fs/dcache.c:425
Inline: False
```
**Symbols:**

```
c0586f90-c0587044: d_shrink_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049ed40)
Location: fs/dcache.c:425
Inline: False
```
**Symbols:**

```
c00000000049ed40-c00000000049edd8: d_shrink_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_shrink_add(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026bc88)
Location: fs/dcache.c:425
Inline: False
```
**Symbols:**

```
ffffffe00026bc88-ffffffe00026bd10: d_shrink_add (STB_LOCAL)
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
In fs/dcache.c (ffffffff812f02e0)
Location: fs/dcache.c:425
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff812e0f10)
Location: fs/dcache.c:425
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff812ee0f0)
Location: fs/dcache.c:425
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
In fs/dcache.c (ffffffff812ff5bd)
Location: fs/dcache.c:425
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
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
</ul>
<b>Arch</b>
<ul>
</ul>
