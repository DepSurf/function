# Function: <code>aa_label_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138aba0)
Location: security/apparmor/label.c:888
Inline: True
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff8138aba0-ffffffff8138ac77: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c5880)
Location: security/apparmor/label.c:888
Inline: True
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff813c5880-ffffffff813c595c: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dcec0)
Location: security/apparmor/label.c:904
Inline: True
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff813dcec0-ffffffff813dcf9c: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ed720)
Location: security/apparmor/label.c:903
Inline: True
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff813ed720-ffffffff813ed7a4: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81415130)
Location: security/apparmor/label.c:903
Inline: True
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81415130-ffffffff814151b4: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81447550)
Location: security/apparmor/label.c:902
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81447550-ffffffff814475d4: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81464480)
Location: security/apparmor/label.c:903
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81464480-ffffffff81464504: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81491720)
Location: security/apparmor/label.c:899
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff81491720-ffffffff814917a5: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ab650)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff814ab650-ffffffff814ab6d5: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150a2a0)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff8150a2a0-ffffffff8150a325: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81527110)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff81527110-ffffffff81527195: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152ca90)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff8152ca90-ffffffff8152cb15: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158ae80)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff8158ae80-ffffffff8158af05: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162c390)
Location: security/apparmor/label.c:928
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff8162c390-ffffffff8162c428: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e0e20)
Location: security/apparmor/label.c:928
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff816e0e20-ffffffff816e0eb8: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171a420)
Location: security/apparmor/label.c:928
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff8171a420-ffffffff8171a4b8: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81758ed0)
Location: security/apparmor/label.c:935
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__label_update
```
**Symbols:**

```
ffffffff81758ed0-ffffffff81758f68: aa_label_insert (STB_GLOBAL)
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
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a2920)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffff8000105a2920-ffff8000105a2a5c: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752ce4)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
c0752ce4-c0752d74: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071d940)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
c00000000071d940-c00000000071da38: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ed000)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffe0003ed000-ffffffe0003ed096: aa_label_insert (STB_GLOBAL)
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
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a3c30)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff814a3c30-ffffffff814a3cb5: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81494650)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff81494650-ffffffff814946d5: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149fcd0)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff8149fcd0-ffffffff8149fd55: aa_label_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *aa_label_insert(struct aa_labelset *ls, struct aa_label *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b8300)
Location: security/apparmor/label.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff814b8300-ffffffff814b8385: aa_label_insert (STB_GLOBAL)
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
