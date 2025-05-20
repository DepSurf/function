# Function: <code>__find_child</code>

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
In security/apparmor/policy.c (ffffffff8137f554)
Location: security/apparmor/policy.c:381
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/policy.c (ffffffff813b8d39)
Location: security/apparmor/policy.c:406
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/policy.c (ffffffff813d00f9)
Location: security/apparmor/policy.c:407
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_find_child
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e36b0)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff813e36b0-ffffffff813e3727: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140a4a0)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff8140a4a0-ffffffff8140a517: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143bde0)
Location: security/apparmor/policy.c:324
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff8143bde0-ffffffff8143be57: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81458c50)
Location: security/apparmor/policy.c:324
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
**Symbols:**

```
ffffffff81458c50-ffffffff81458cc7: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814863d0)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff814863d0-ffffffff81486449: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a0280)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff814a0280-ffffffff814a02f9: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814f9d20)
Location: security/apparmor/policy.c:323
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff814f9d20-ffffffff814f9d9a: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81516e50)
Location: security/apparmor/policy.c:323
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff81516e50-ffffffff81516eca: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151d700)
Location: security/apparmor/policy.c:323
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff8151d700-ffffffff8151d77a: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157b7f0)
Location: security/apparmor/policy.c:323
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff8157b7f0-ffffffff8157b86a: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81619c00)
Location: security/apparmor/policy.c:366
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff81619c00-ffffffff81619c8b: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816ccb40)
Location: security/apparmor/policy.c:372
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff816ccb40-ffffffff816ccbcb: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff817055e0)
Location: security/apparmor/policy.c:410
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff817055e0-ffffffff8170566b: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81742ee0)
Location: security/apparmor/policy.c:437
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff81742ee0-ffffffff81742f6b: __find_child (STB_LOCAL)
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
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff8000105960a8)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffff8000105960a8-ffff800010596140: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c0747188)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
c0747188-c074720c: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070ba20)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
c00000000070ba20-c00000000070bb08: __find_child (STB_LOCAL)
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
In security/apparmor/policy.c (ffffffe0003e2e6c)
Location: security/apparmor/policy.c:319
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
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
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81498860)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff81498860-ffffffff814988d9: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81489280)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff81489280-ffffffff814892f9: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81494900)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff81494900-ffffffff81494979: __find_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_profile *__find_child(struct list_head *head, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814ac920)
Location: security/apparmor/policy.c:319
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_find_child
```
**Symbols:**

```
ffffffff814ac920-ffffffff814ac999: __find_child (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
