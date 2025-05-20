# Function: <code>__label_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389b00)
Location: security/apparmor/label.c:548
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_remove
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81389b00-ffffffff81389bfc: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c4730)
Location: security/apparmor/label.c:548
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff813c4730-ffffffff813c482c: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dbd80)
Location: security/apparmor/label.c:564
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff813dbd80-ffffffff813dbe7c: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ecd10)
Location: security/apparmor/label.c:568
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff813ecd10-ffffffff813ecd70: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414510)
Location: security/apparmor/label.c:568
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff81414510-ffffffff81414570: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814468a0)
Location: security/apparmor/label.c:567
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff814468a0-ffffffff81446905: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814639a0)
Location: security/apparmor/label.c:568
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff814639a0-ffffffff81463a05: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490c50)
Location: security/apparmor/label.c:564
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff81490c50-ffffffff81490cbd: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aab00)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff814aab00-ffffffff814aab6d: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815090c0)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff815090c0-ffffffff81509131: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526080)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff81526080-ffffffff815260f1: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152ba10)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff8152ba10-ffffffff8152ba81: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81589df0)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff81589df0-ffffffff81589e61: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162afa0)
Location: security/apparmor/label.c:593
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff8162afa0-ffffffff8162b021: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816df810)
Location: security/apparmor/label.c:593
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff816df810-ffffffff816df891: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81718e60)
Location: security/apparmor/label.c:593
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff81718e60-ffffffff81718ee1: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff817578f0)
Location: security/apparmor/label.c:599
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff817578f0-ffffffff81757971: __label_remove (STB_LOCAL)
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
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a19b8)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffff8000105a19b8-ffff8000105a1a4c: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752144)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
c0752144-c07521b0: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071c620)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
c00000000071c620-c00000000071c6e4: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec53c)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffe0003ec53c-ffffffe0003ec5c4: __label_remove (STB_LOCAL)
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
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a30e0)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff814a30e0-ffffffff814a314d: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81493b00)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff81493b00-ffffffff81493b6d: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f180)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff8149f180-ffffffff8149f1ed: __label_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __label_remove(struct aa_label *label, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b77b0)
Location: security/apparmor/label.c:591
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
**Symbols:**

```
ffffffff814b77b0-ffffffff814b781d: __label_remove (STB_LOCAL)
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
