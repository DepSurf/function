# Function: <code>label_free_or_put_new</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dbb30)
Location: security/apparmor/label.c:390
Inline: True
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff813dbb30-ffffffff813dbb6c: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ecf40)
Location: security/apparmor/label.c:396
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff813ecf40-ffffffff813ecf7b: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814148a0)
Location: security/apparmor/label.c:396
Inline: True
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814148a0-ffffffff814148e8: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446c60)
Location: security/apparmor/label.c:396
Inline: True
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff81446c60-ffffffff81446ca1: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463b90)
Location: security/apparmor/label.c:396
Inline: True
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff81463b90-ffffffff81463bd1: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490e30)
Location: security/apparmor/label.c:392
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff81490e30-ffffffff81490e73: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aace0)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814aace0-ffffffff814aad23: label_free_or_put_new (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff8150a5a9)
Location: security/apparmor/label.c:387
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
In security/apparmor/label.c (ffffffff8152741c)
Location: security/apparmor/label.c:387
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
In security/apparmor/label.c (ffffffff8152cd8b)
Location: security/apparmor/label.c:387
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
In security/apparmor/label.c (ffffffff8158b17b)
Location: security/apparmor/label.c:387
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
In security/apparmor/label.c (ffffffff8162c6d1)
Location: security/apparmor/label.c:390
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
In security/apparmor/label.c (ffffffff816e1171)
Location: security/apparmor/label.c:390
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
In security/apparmor/label.c (ffffffff8171a769)
Location: security/apparmor/label.c:390
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
In security/apparmor/label.c (ffffffff8175921b)
Location: security/apparmor/label.c:396
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1ca8)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffff8000105a1ca8-ffff8000105a1d0c: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c07523ac)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
c07523ac-c075240c: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071ca90)
Location: security/apparmor/label.c:386
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
c00000000071ca90-c00000000071cb20: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec8f8)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffe0003ec8f8-ffffffe0003ec956: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a32c0)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814a32c0-ffffffff814a3303: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81493ce0)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff81493ce0-ffffffff81493d23: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f360)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff8149f360-ffffffff8149f3a3: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void label_free_or_put_new(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7990)
Location: security/apparmor/label.c:386
Inline: True
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814b7990-ffffffff814b79d3: label_free_or_put_new (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
