# Function: <code>aa_find_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137fc10)
Location: security/apparmor/policy.c:409
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_null_profile
```
**Symbols:**

```
ffffffff8137fc10-ffffffff8137fcaa: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b95d0)
Location: security/apparmor/policy.c:434
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_null_profile
```
**Symbols:**

```
ffffffff813b95d0-ffffffff813b9677: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d0990)
Location: security/apparmor/policy.c:435
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_null_profile
```
**Symbols:**

```
ffffffff813d0990-ffffffff813d0a37: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e3e60)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff813e3e60-ffffffff813e3ec1: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140ac50)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff8140ac50-ffffffff8140acd0: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143c520)
Location: security/apparmor/policy.c:336
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff8143c520-ffffffff8143c5a0: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81459390)
Location: security/apparmor/policy.c:336
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff81459390-ffffffff81459410: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81486b30)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff81486b30-ffffffff81486b90: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a09e0)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff814a09e0-ffffffff814a0a40: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814faac0)
Location: security/apparmor/policy.c:335
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff814faac0-ffffffff814fab2b: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81517840)
Location: security/apparmor/policy.c:335
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff81517840-ffffffff815178b5: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151e0f0)
Location: security/apparmor/policy.c:335
Inline: False
Direct callers:
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff8151e0f0-ffffffff8151e161: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157c240)
Location: security/apparmor/policy.c:335
Inline: False
Direct callers:
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff8157c240-ffffffff8157c2b1: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8161a980)
Location: security/apparmor/policy.c:378
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff8161a980-ffffffff8161aa15: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816cd980)
Location: security/apparmor/policy.c:384
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_learning_profile
```
**Symbols:**

```
ffffffff816cd980-ffffffff816cda15: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff817065e0)
Location: security/apparmor/policy.c:422
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_learning_profile
```
**Symbols:**

```
ffffffff817065e0-ffffffff81706671: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81744060)
Location: security/apparmor/policy.c:449
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_learning_profile
```
**Symbols:**

```
ffffffff81744060-ffffffff817440f1: aa_find_child (STB_GLOBAL)
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
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010596758)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffff800010596758-ffff8000105967b4: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c074783c)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
c074783c-c0747884: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070c4a0)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
c00000000070c4a0-c00000000070c540: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e34c0)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffe0003e34c0-ffffffe0003e356c: aa_find_child (STB_GLOBAL)
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
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81498fc0)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff81498fc0-ffffffff81499020: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814899e0)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff814899e0-ffffffff81489a40: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81495060)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff81495060-ffffffff814950c0: aa_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_profile *aa_find_child(struct aa_profile *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814ad080)
Location: security/apparmor/policy.c:331
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff814ad080-ffffffff814ad0f8: aa_find_child (STB_GLOBAL)
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
