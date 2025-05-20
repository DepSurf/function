# Function: <code>vec_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389320)
Location: security/apparmor/label.c:796
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff81389320-ffffffff81389400: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c3ee0)
Location: security/apparmor/label.c:796
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff813c3ee0-ffffffff813c3fc0: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813db470)
Location: security/apparmor/label.c:812
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff813db470-ffffffff813db550: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813eca00)
Location: security/apparmor/label.c:811
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff813eca00-ffffffff813eca59: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814143c0)
Location: security/apparmor/label.c:811
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814143c0-ffffffff81414419: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446750)
Location: security/apparmor/label.c:810
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff81446750-ffffffff814467a9: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463670)
Location: security/apparmor/label.c:811
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff81463670-ffffffff814636c9: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490920)
Location: security/apparmor/label.c:807
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff81490920-ffffffff8149097b: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aa7e0)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814aa7e0-ffffffff814aa83b: vec_find (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff8150c999)
Location: security/apparmor/label.c:834
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
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
In security/apparmor/label.c (ffffffff8152984f)
Location: security/apparmor/label.c:834
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
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
In security/apparmor/label.c (ffffffff8152f9e7)
Location: security/apparmor/label.c:834
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
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
In security/apparmor/label.c (ffffffff8158de07)
Location: security/apparmor/label.c:834
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
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
In security/apparmor/label.c (ffffffff8162eba7)
Location: security/apparmor/label.c:836
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
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
In security/apparmor/label.c (ffffffff816e3773)
Location: security/apparmor/label.c:836
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
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
In security/apparmor/label.c (ffffffff8171ccc6)
Location: security/apparmor/label.c:836
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
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
In security/apparmor/label.c (ffffffff8175b715)
Location: security/apparmor/label.c:844
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
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
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1570)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffff8000105a1570-ffff8000105a1648: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0751df8)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
c0751df8-c0751e5c: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071c100)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
c00000000071c100-c00000000071c19c: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec1a0)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffe0003ec1a0-ffffffe0003ec204: vec_find (STB_LOCAL)
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
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a2dc0)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814a2dc0-ffffffff814a2e1b: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814937e0)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814937e0-ffffffff8149383b: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149ee60)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff8149ee60-ffffffff8149eebb: vec_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *vec_find(struct aa_profile **vec, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7490)
Location: security/apparmor/label.c:834
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_find
  - security/apparmor/label.c:aa_vec_find_or_create_label
```
**Symbols:**

```
ffffffff814b7490-ffffffff814b74eb: vec_find (STB_LOCAL)
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
