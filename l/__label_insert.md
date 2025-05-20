# Function: <code>__label_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389c90)
Location: security/apparmor/label.c:623
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81389c90-ffffffff81389f59: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c48c0)
Location: security/apparmor/label.c:623
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff813c48c0-ffffffff813c4b9a: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dbf10)
Location: security/apparmor/label.c:639
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff813dbf10-ffffffff813dc1ea: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ecfc0)
Location: security/apparmor/label.c:640
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff813ecfc0-ffffffff813ed0bc: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414610)
Location: security/apparmor/label.c:640
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81414610-ffffffff8141473f: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814469b0)
Location: security/apparmor/label.c:639
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff814469b0-ffffffff81446adf: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463a60)
Location: security/apparmor/label.c:640
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81463a60-ffffffff81463b8f: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490d10)
Location: security/apparmor/label.c:636
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81490d10-ffffffff81490e2a: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aabc0)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff814aabc0-ffffffff814aacda: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81509350)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81509350-ffffffff815095cc: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526240)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81526240-ffffffff8152643b: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152bbd0)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff8152bbd0-ffffffff8152bdc3: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81589fb0)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81589fb0-ffffffff8158a1a3: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162b190)
Location: security/apparmor/label.c:665
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff8162b190-ffffffff8162b3c3: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816dfa30)
Location: security/apparmor/label.c:665
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff816dfa30-ffffffff816dfc5a: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81719080)
Location: security/apparmor/label.c:665
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81719080-ffffffff8171927e: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81757b10)
Location: security/apparmor/label.c:672
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81757b10-ffffffff81757d16: __label_insert (STB_LOCAL)
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
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1d90)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffff8000105a1d90-ffff8000105a1ef0: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752474)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
c0752474-c075258c: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071cbd0)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
c00000000071cbd0-c00000000071ce1c: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec636)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffe0003ec636-ffffffe0003ec738: __label_insert (STB_LOCAL)
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
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a31a0)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff814a31a0-ffffffff814a32ba: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81493bc0)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81493bc0-ffffffff81493cda: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f240)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff8149f240-ffffffff8149f35a: __label_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *__label_insert(struct aa_labelset *ls, struct aa_label *label, bool replace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7870)
Location: security/apparmor/label.c:663
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff814b7870-ffffffff814b798a: __label_insert (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
